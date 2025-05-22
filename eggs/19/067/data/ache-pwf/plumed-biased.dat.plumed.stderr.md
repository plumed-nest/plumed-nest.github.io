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
[pkrvmf6wy0o8zjz:40834] *** Process received signal ***
[pkrvmf6wy0o8zjz:40834] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40834] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40834] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6322c45330]
[pkrvmf6wy0o8zjz:40834] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6322c9eb2c]
[pkrvmf6wy0o8zjz:40834] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6322c4527e]
[pkrvmf6wy0o8zjz:40834] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6322c288ff]
[pkrvmf6wy0o8zjz:40834] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63230a5ff5]
[pkrvmf6wy0o8zjz:40834] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63230bb0da]
[pkrvmf6wy0o8zjz:40834] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63230a5a55]
[pkrvmf6wy0o8zjz:40834] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63230a5a6f]
[pkrvmf6wy0o8zjz:40834] [ 8] plumed(+0x146dd)[0x55f173d1e6dd]
[pkrvmf6wy0o8zjz:40834] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6322c2a1ca]
[pkrvmf6wy0o8zjz:40834] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6322c2a28b]
[pkrvmf6wy0o8zjz:40834] [11] plumed(+0x15365)[0x55f173d1f365]
[pkrvmf6wy0o8zjz:40834] *** End of error message ***
</pre>
{% endraw %}
