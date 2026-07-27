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
[runnervmvrwv9:09177] *** Process received signal ***
[runnervmvrwv9:09177] Signal: Aborted (6)
[runnervmvrwv9:09177] Signal code:  (-6)
[runnervmvrwv9:09177] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb423a45330]
[runnervmvrwv9:09177] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb423a9eb2c]
[runnervmvrwv9:09177] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb423a4527e]
[runnervmvrwv9:09177] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb423a288ff]
[runnervmvrwv9:09177] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb423ea5ff5]
[runnervmvrwv9:09177] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb423ebb0da]
[runnervmvrwv9:09177] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb423ea5a55]
[runnervmvrwv9:09177] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb423ea5a6f]
[runnervmvrwv9:09177] [ 8] plumed_master(+0x146dd)[0x561020e4c6dd]
[runnervmvrwv9:09177] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb423a2a1ca]
[runnervmvrwv9:09177] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb423a2a28b]
[runnervmvrwv9:09177] [11] plumed_master(+0x15365)[0x561020e4d365]
[runnervmvrwv9:09177] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmvrwv9:09176] *** Process received signal ***
[runnervmvrwv9:09176] Signal: Aborted (6)
[runnervmvrwv9:09176] Signal code:  (-6)
[runnervmvrwv9:09176] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3969e45330]
[runnervmvrwv9:09176] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3969e9eb2c]
[runnervmvrwv9:09176] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3969e4527e]
[runnervmvrwv9:09176] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3969e288ff]
[runnervmvrwv9:09176] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f396a2a5ff5]
[runnervmvrwv9:09176] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f396a2bb0da]
[runnervmvrwv9:09176] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f396a2a5a55]
[runnervmvrwv9:09176] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f396a2a5a6f]
[runnervmvrwv9:09176] [ 8] plumed_master(+0x146dd)[0x559bb579c6dd]
[runnervmvrwv9:09176] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3969e2a1ca]
[runnervmvrwv9:09176] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3969e2a28b]
[runnervmvrwv9:09176] [11] plumed_master(+0x15365)[0x559bb579d365]
[runnervmvrwv9:09176] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmvrwv9 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
