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
[pkrvmf6wy0o8zjz:64095] *** Process received signal ***
[pkrvmf6wy0o8zjz:64095] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64095] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64095] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb21245330]
[pkrvmf6wy0o8zjz:64095] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb2129eb2c]
[pkrvmf6wy0o8zjz:64095] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb2124527e]
[pkrvmf6wy0o8zjz:64095] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb212288ff]
[pkrvmf6wy0o8zjz:64095] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb216a5ff5]
[pkrvmf6wy0o8zjz:64095] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb216bb0da]
[pkrvmf6wy0o8zjz:64095] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb216a5a55]
[pkrvmf6wy0o8zjz:64095] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb216a5a6f]
[pkrvmf6wy0o8zjz:64095] [ 8] plumed(+0x146dd)[0x563a08f186dd]
[pkrvmf6wy0o8zjz:64095] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb2122a1ca]
[pkrvmf6wy0o8zjz:64095] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb2122a28b]
[pkrvmf6wy0o8zjz:64095] [11] plumed(+0x15365)[0x563a08f19365]
[pkrvmf6wy0o8zjz:64095] *** End of error message ***
</pre>
{% endraw %}
