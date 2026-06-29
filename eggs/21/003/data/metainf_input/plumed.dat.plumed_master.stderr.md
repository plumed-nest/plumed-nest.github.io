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
[runnervmmklqx:10346] *** Process received signal ***
[runnervmmklqx:10346] Signal: Aborted (6)
[runnervmmklqx:10346] Signal code:  (-6)
[runnervmmklqx:10346] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5cabe45330]
[runnervmmklqx:10346] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5cabe9eb2c]
[runnervmmklqx:10346] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5cabe4527e]
[runnervmmklqx:10346] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5cabe288ff]
[runnervmmklqx:10346] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5cac2a5ff5]
[runnervmmklqx:10346] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5cac2bb0da]
[runnervmmklqx:10346] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5cac2a5a55]
[runnervmmklqx:10346] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5cac2a5a6f]
[runnervmmklqx:10346] [ 8] plumed_master(+0x146dd)[0x55abc0f526dd]
[runnervmmklqx:10346] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5cabe2a1ca]
[runnervmmklqx:10346] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5cabe2a28b]
[runnervmmklqx:10346] [11] plumed_master(+0x15365)[0x55abc0f53365]
[runnervmmklqx:10346] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmmklqx:10345] *** Process received signal ***
[runnervmmklqx:10345] Signal: Aborted (6)
[runnervmmklqx:10345] Signal code:  (-6)
[runnervmmklqx:10345] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdbbee45330]
[runnervmmklqx:10345] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdbbee9eb2c]
[runnervmmklqx:10345] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdbbee4527e]
[runnervmmklqx:10345] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdbbee288ff]
[runnervmmklqx:10345] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdbbf2a5ff5]
[runnervmmklqx:10345] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdbbf2bb0da]
[runnervmmklqx:10345] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdbbf2a5a55]
[runnervmmklqx:10345] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdbbf2a5a6f]
[runnervmmklqx:10345] [ 8] plumed_master(+0x146dd)[0x55e96d2dd6dd]
[runnervmmklqx:10345] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdbbee2a1ca]
[runnervmmklqx:10345] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdbbee2a28b]
[runnervmmklqx:10345] [11] plumed_master(+0x15365)[0x55e96d2de365]
[runnervmmklqx:10345] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmmklqx exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
