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
[pkrvmf6wy0o8zjz:34859] *** Process received signal ***
[pkrvmf6wy0o8zjz:34859] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34859] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34859] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f863a445330]
[pkrvmf6wy0o8zjz:34859] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f863a49eb2c]
[pkrvmf6wy0o8zjz:34859] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f863a44527e]
[pkrvmf6wy0o8zjz:34859] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f863a4288ff]
[pkrvmf6wy0o8zjz:34859] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f863a8a5ff5]
[pkrvmf6wy0o8zjz:34859] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f863a8bb0da]
[pkrvmf6wy0o8zjz:34859] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f863a8a5a55]
[pkrvmf6wy0o8zjz:34859] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f863a8a5a6f]
[pkrvmf6wy0o8zjz:34859] [ 8] plumed_master(+0x146dd)[0x563c760396dd]
[pkrvmf6wy0o8zjz:34859] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f863a42a1ca]
[pkrvmf6wy0o8zjz:34859] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f863a42a28b]
[pkrvmf6wy0o8zjz:34859] [11] plumed_master(+0x15365)[0x563c7603a365]
[pkrvmf6wy0o8zjz:34859] *** End of error message ***
</pre>
{% endraw %}
