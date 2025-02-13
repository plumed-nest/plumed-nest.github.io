**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1657-925:10140] *** Process received signal ***
[fv-az1657-925:10140] Signal: Aborted (6)
[fv-az1657-925:10140] Signal code:  (-6)
[fv-az1657-925:10140] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdde1045330]
[fv-az1657-925:10140] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdde109eb2c]
[fv-az1657-925:10140] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdde104527e]
[fv-az1657-925:10140] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdde10288ff]
[fv-az1657-925:10140] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdde14a5ff5]
[fv-az1657-925:10140] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdde14bb0da]
[fv-az1657-925:10140] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdde14a5a55]
[fv-az1657-925:10140] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdde14a5a6f]
[fv-az1657-925:10140] [ 8] plumed_master(+0x146dd)[0x56142d9266dd]
[fv-az1657-925:10140] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdde102a1ca]
[fv-az1657-925:10140] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdde102a28b]
[fv-az1657-925:10140] [11] plumed_master(+0x15365)[0x56142d927365]
[fv-az1657-925:10140] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1657-925:10139] *** Process received signal ***
[fv-az1657-925:10139] Signal: Aborted (6)
[fv-az1657-925:10139] Signal code:  (-6)
[fv-az1657-925:10139] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe816a45330]
[fv-az1657-925:10139] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe816a9eb2c]
[fv-az1657-925:10139] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe816a4527e]
[fv-az1657-925:10139] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe816a288ff]
[fv-az1657-925:10139] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe816ea5ff5]
[fv-az1657-925:10139] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe816ebb0da]
[fv-az1657-925:10139] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe816ea5a55]
[fv-az1657-925:10139] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe816ea5a6f]
[fv-az1657-925:10139] [ 8] plumed_master(+0x146dd)[0x557151aa56dd]
[fv-az1657-925:10139] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe816a2a1ca]
[fv-az1657-925:10139] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe816a2a28b]
[fv-az1657-925:10139] [11] plumed_master(+0x15365)[0x557151aa6365]
[fv-az1657-925:10139] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1657-925 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
