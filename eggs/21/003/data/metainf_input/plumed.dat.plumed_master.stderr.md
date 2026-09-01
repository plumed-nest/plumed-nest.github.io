**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmgx7h7:09148] *** Process received signal ***
[runnervmgx7h7:09148] Signal: Aborted (6)
[runnervmgx7h7:09148] Signal code:  (-6)
[runnervmgx7h7:09148] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a0ea45330]
[runnervmgx7h7:09148] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a0ea9ec0c]
[runnervmgx7h7:09148] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a0ea4527e]
[runnervmgx7h7:09148] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a0ea288ff]
[runnervmgx7h7:09148] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a0eea5ff5]
[runnervmgx7h7:09148] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a0eebb0da]
[runnervmgx7h7:09148] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a0eea5a55]
[runnervmgx7h7:09148] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a0eea5a6f]
[runnervmgx7h7:09148] [ 8] plumed_master(+0x146dd)[0x55588be666dd]
[runnervmgx7h7:09148] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a0ea2a1ca]
[runnervmgx7h7:09148] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a0ea2a28b]
[runnervmgx7h7:09148] [11] plumed_master(+0x15365)[0x55588be67365]
[runnervmgx7h7:09148] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmgx7h7:09147] *** Process received signal ***
[runnervmgx7h7:09147] Signal: Aborted (6)
[runnervmgx7h7:09147] Signal code:  (-6)
[runnervmgx7h7:09147] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4eaa645330]
[runnervmgx7h7:09147] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4eaa69ec0c]
[runnervmgx7h7:09147] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4eaa64527e]
[runnervmgx7h7:09147] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4eaa6288ff]
[runnervmgx7h7:09147] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4eaaaa5ff5]
[runnervmgx7h7:09147] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4eaaabb0da]
[runnervmgx7h7:09147] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4eaaaa5a55]
[runnervmgx7h7:09147] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4eaaaa5a6f]
[runnervmgx7h7:09147] [ 8] plumed_master(+0x146dd)[0x56216b7ec6dd]
[runnervmgx7h7:09147] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4eaa62a1ca]
[runnervmgx7h7:09147] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4eaa62a28b]
[runnervmgx7h7:09147] [11] plumed_master(+0x15365)[0x56216b7ed365]
[runnervmgx7h7:09147] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmgx7h7 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
