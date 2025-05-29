**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmf6wy0o8zjz:68557] *** Process received signal ***
[pkrvmf6wy0o8zjz:68557] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68557] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68557] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f11fd645330]
[pkrvmf6wy0o8zjz:68557] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f11fd69eb2c]
[pkrvmf6wy0o8zjz:68557] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f11fd64527e]
[pkrvmf6wy0o8zjz:68557] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f11fd6288ff]
[pkrvmf6wy0o8zjz:68557] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f11fdaa5ff5]
[pkrvmf6wy0o8zjz:68557] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f11fdabb0da]
[pkrvmf6wy0o8zjz:68557] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f11fdaa5a55]
[pkrvmf6wy0o8zjz:68557] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f11fdaa5a6f]
[pkrvmf6wy0o8zjz:68557] [ 8] plumed(+0x146dd)[0x555af415e6dd]
[pkrvmf6wy0o8zjz:68557] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f11fd62a1ca]
[pkrvmf6wy0o8zjz:68557] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f11fd62a28b]
[pkrvmf6wy0o8zjz:68557] [11] plumed(+0x15365)[0x555af415f365]
[pkrvmf6wy0o8zjz:68557] *** End of error message ***
</pre>
{% endraw %}
