**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmf6wy0o8zjz:65926] *** Process received signal ***
[pkrvmf6wy0o8zjz:65926] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65926] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65926] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b62045330]
[pkrvmf6wy0o8zjz:65926] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b6209eb2c]
[pkrvmf6wy0o8zjz:65926] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b6204527e]
[pkrvmf6wy0o8zjz:65926] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b620288ff]
[pkrvmf6wy0o8zjz:65926] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b624a5ff5]
[pkrvmf6wy0o8zjz:65926] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b624bb0da]
[pkrvmf6wy0o8zjz:65926] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b624a5a55]
[pkrvmf6wy0o8zjz:65926] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b624a5a6f]
[pkrvmf6wy0o8zjz:65926] [ 8] plumed(+0x146dd)[0x55bb272ca6dd]
[pkrvmf6wy0o8zjz:65926] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b6202a1ca]
[pkrvmf6wy0o8zjz:65926] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b6202a28b]
[pkrvmf6wy0o8zjz:65926] [11] plumed(+0x15365)[0x55bb272cb365]
[pkrvmf6wy0o8zjz:65926] *** End of error message ***
</pre>
{% endraw %}
