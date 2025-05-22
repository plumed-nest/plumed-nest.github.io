**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmf6wy0o8zjz:34843] *** Process received signal ***
[pkrvmf6wy0o8zjz:34843] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34843] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f95645330]
[pkrvmf6wy0o8zjz:34843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f9569eb2c]
[pkrvmf6wy0o8zjz:34843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f9564527e]
[pkrvmf6wy0o8zjz:34843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f956288ff]
[pkrvmf6wy0o8zjz:34843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f95aa5ff5]
[pkrvmf6wy0o8zjz:34843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f95abb0da]
[pkrvmf6wy0o8zjz:34843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f95aa5a55]
[pkrvmf6wy0o8zjz:34843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f95aa5a6f]
[pkrvmf6wy0o8zjz:34843] [ 8] plumed(+0x146dd)[0x55b209fe06dd]
[pkrvmf6wy0o8zjz:34843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f9562a1ca]
[pkrvmf6wy0o8zjz:34843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f9562a28b]
[pkrvmf6wy0o8zjz:34843] [11] plumed(+0x15365)[0x55b209fe1365]
[pkrvmf6wy0o8zjz:34843] *** End of error message ***
</pre>
{% endraw %}
