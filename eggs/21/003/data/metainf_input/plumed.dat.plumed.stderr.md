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
[pkrvmq0rgcvqdmg:11194] *** Process received signal ***
[pkrvmq0rgcvqdmg:11194] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11194] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11194] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6c3e45330]
[pkrvmq0rgcvqdmg:11194] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6c3e9eb2c]
[pkrvmq0rgcvqdmg:11194] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6c3e4527e]
[pkrvmq0rgcvqdmg:11194] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6c3e288ff]
[pkrvmq0rgcvqdmg:11194] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6c42a5ff5]
[pkrvmq0rgcvqdmg:11194] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6c42bb0da]
[pkrvmq0rgcvqdmg:11194] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6c42a5a55]
[pkrvmq0rgcvqdmg:11194] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6c42a5a6f]
[pkrvmq0rgcvqdmg:11194] [ 8] plumed(+0x146dd)[0x55a139d916dd]
[pkrvmq0rgcvqdmg:11194] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6c3e2a1ca]
[pkrvmq0rgcvqdmg:11194] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6c3e2a28b]
[pkrvmq0rgcvqdmg:11194] [11] plumed(+0x15365)[0x55a139d92365]
[pkrvmq0rgcvqdmg:11194] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmq0rgcvqdmg:11195] *** Process received signal ***
[pkrvmq0rgcvqdmg:11195] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11195] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11195] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa19cc45330]
[pkrvmq0rgcvqdmg:11195] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa19cc9eb2c]
[pkrvmq0rgcvqdmg:11195] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa19cc4527e]
[pkrvmq0rgcvqdmg:11195] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa19cc288ff]
[pkrvmq0rgcvqdmg:11195] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa19d0a5ff5]
[pkrvmq0rgcvqdmg:11195] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa19d0bb0da]
[pkrvmq0rgcvqdmg:11195] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa19d0a5a55]
[pkrvmq0rgcvqdmg:11195] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa19d0a5a6f]
[pkrvmq0rgcvqdmg:11195] [ 8] plumed(+0x146dd)[0x557aeaf1e6dd]
[pkrvmq0rgcvqdmg:11195] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa19cc2a1ca]
[pkrvmq0rgcvqdmg:11195] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa19cc2a28b]
[pkrvmq0rgcvqdmg:11195] [11] plumed(+0x15365)[0x557aeaf1f365]
[pkrvmq0rgcvqdmg:11195] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmq0rgcvqdmg exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
