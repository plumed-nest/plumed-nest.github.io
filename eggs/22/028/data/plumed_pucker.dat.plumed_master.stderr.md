**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmf6wy0o8zjz:64111] *** Process received signal ***
[pkrvmf6wy0o8zjz:64111] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64111] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64111] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff648645330]
[pkrvmf6wy0o8zjz:64111] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff64869eb2c]
[pkrvmf6wy0o8zjz:64111] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff64864527e]
[pkrvmf6wy0o8zjz:64111] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6486288ff]
[pkrvmf6wy0o8zjz:64111] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff648aa5ff5]
[pkrvmf6wy0o8zjz:64111] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff648abb0da]
[pkrvmf6wy0o8zjz:64111] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff648aa5a55]
[pkrvmf6wy0o8zjz:64111] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff648aa5a6f]
[pkrvmf6wy0o8zjz:64111] [ 8] plumed_master(+0x146dd)[0x5556dc6ea6dd]
[pkrvmf6wy0o8zjz:64111] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff64862a1ca]
[pkrvmf6wy0o8zjz:64111] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff64862a28b]
[pkrvmf6wy0o8zjz:64111] [11] plumed_master(+0x15365)[0x5556dc6eb365]
[pkrvmf6wy0o8zjz:64111] *** End of error message ***
</pre>
{% endraw %}
