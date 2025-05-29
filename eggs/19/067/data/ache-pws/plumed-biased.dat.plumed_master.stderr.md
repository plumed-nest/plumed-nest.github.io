**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmf6wy0o8zjz:66038] *** Process received signal ***
[pkrvmf6wy0o8zjz:66038] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66038] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66038] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2b3dc45330]
[pkrvmf6wy0o8zjz:66038] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2b3dc9eb2c]
[pkrvmf6wy0o8zjz:66038] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2b3dc4527e]
[pkrvmf6wy0o8zjz:66038] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2b3dc288ff]
[pkrvmf6wy0o8zjz:66038] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2b3e0a5ff5]
[pkrvmf6wy0o8zjz:66038] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2b3e0bb0da]
[pkrvmf6wy0o8zjz:66038] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2b3e0a5a55]
[pkrvmf6wy0o8zjz:66038] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2b3e0a5a6f]
[pkrvmf6wy0o8zjz:66038] [ 8] plumed_master(+0x146dd)[0x55894eb876dd]
[pkrvmf6wy0o8zjz:66038] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2b3dc2a1ca]
[pkrvmf6wy0o8zjz:66038] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2b3dc2a28b]
[pkrvmf6wy0o8zjz:66038] [11] plumed_master(+0x15365)[0x55894eb88365]
[pkrvmf6wy0o8zjz:66038] *** End of error message ***
</pre>
{% endraw %}
