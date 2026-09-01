**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmgx7h7:09113] *** Process received signal ***
[runnervmgx7h7:09113] Signal: Aborted (6)
[runnervmgx7h7:09113] Signal code:  (-6)
[runnervmgx7h7:09113] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9154445330]
[runnervmgx7h7:09113] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f915449ec0c]
[runnervmgx7h7:09113] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f915444527e]
[runnervmgx7h7:09113] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91544288ff]
[runnervmgx7h7:09113] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91548a5ff5]
[runnervmgx7h7:09113] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91548bb0da]
[runnervmgx7h7:09113] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91548a5a55]
[runnervmgx7h7:09113] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91548a5a6f]
[runnervmgx7h7:09113] [ 8] plumed(+0x146dd)[0x5572430e76dd]
[runnervmgx7h7:09113] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f915442a1ca]
[runnervmgx7h7:09113] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f915442a28b]
[runnervmgx7h7:09113] [11] plumed(+0x15365)[0x5572430e8365]
[runnervmgx7h7:09113] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmgx7h7:09114] *** Process received signal ***
[runnervmgx7h7:09114] Signal: Aborted (6)
[runnervmgx7h7:09114] Signal code:  (-6)
[runnervmgx7h7:09114] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f662dc45330]
[runnervmgx7h7:09114] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f662dc9ec0c]
[runnervmgx7h7:09114] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f662dc4527e]
[runnervmgx7h7:09114] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f662dc288ff]
[runnervmgx7h7:09114] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f662e0a5ff5]
[runnervmgx7h7:09114] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f662e0bb0da]
[runnervmgx7h7:09114] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f662e0a5a55]
[runnervmgx7h7:09114] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f662e0a5a6f]
[runnervmgx7h7:09114] [ 8] plumed(+0x146dd)[0x55e235bb26dd]
[runnervmgx7h7:09114] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f662dc2a1ca]
[runnervmgx7h7:09114] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f662dc2a28b]
[runnervmgx7h7:09114] [11] plumed(+0x15365)[0x55e235bb3365]
[runnervmgx7h7:09114] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node runnervmgx7h7 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
