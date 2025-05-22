**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmf6wy0o8zjz:38746] *** Process received signal ***
[pkrvmf6wy0o8zjz:38746] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38746] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f49b3c45330]
[pkrvmf6wy0o8zjz:38746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f49b3c9eb2c]
[pkrvmf6wy0o8zjz:38746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f49b3c4527e]
[pkrvmf6wy0o8zjz:38746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f49b3c288ff]
[pkrvmf6wy0o8zjz:38746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f49b40a5ff5]
[pkrvmf6wy0o8zjz:38746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f49b40bb0da]
[pkrvmf6wy0o8zjz:38746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f49b40a5a55]
[pkrvmf6wy0o8zjz:38746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f49b40a5a6f]
[pkrvmf6wy0o8zjz:38746] [ 8] plumed(+0x146dd)[0x56056c3f46dd]
[pkrvmf6wy0o8zjz:38746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f49b3c2a1ca]
[pkrvmf6wy0o8zjz:38746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f49b3c2a28b]
[pkrvmf6wy0o8zjz:38746] [11] plumed(+0x15365)[0x56056c3f5365]
[pkrvmf6wy0o8zjz:38746] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmf6wy0o8zjz:38747] *** Process received signal ***
[pkrvmf6wy0o8zjz:38747] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38747] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38747] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb773e45330]
[pkrvmf6wy0o8zjz:38747] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb773e9eb2c]
[pkrvmf6wy0o8zjz:38747] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb773e4527e]
[pkrvmf6wy0o8zjz:38747] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb773e288ff]
[pkrvmf6wy0o8zjz:38747] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7742a5ff5]
[pkrvmf6wy0o8zjz:38747] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7742bb0da]
[pkrvmf6wy0o8zjz:38747] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7742a5a55]
[pkrvmf6wy0o8zjz:38747] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7742a5a6f]
[pkrvmf6wy0o8zjz:38747] [ 8] plumed(+0x146dd)[0x5591fb5046dd]
[pkrvmf6wy0o8zjz:38747] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb773e2a1ca]
[pkrvmf6wy0o8zjz:38747] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb773e2a28b]
[pkrvmf6wy0o8zjz:38747] [11] plumed(+0x15365)[0x5591fb505365]
[pkrvmf6wy0o8zjz:38747] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmf6wy0o8zjz exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
