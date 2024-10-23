**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az585-767:08065] *** Process received signal ***
[fv-az585-767:08065] Signal: Aborted (6)
[fv-az585-767:08065] Signal code:  (-6)
[fv-az585-767:08065] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9e07a42520]
[fv-az585-767:08065] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9e07a969fc]
[fv-az585-767:08065] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9e07a42476]
[fv-az585-767:08065] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9e07a287f3]
[fv-az585-767:08065] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9e07ea2b9e]
[fv-az585-767:08065] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9e07eae20c]
[fv-az585-767:08065] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9e07eae277]
[fv-az585-767:08065] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9e07eae52b]
[fv-az585-767:08065] [ 8] plumed_master(+0x14254)[0x558a26834254]
[fv-az585-767:08065] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9e07a29d90]
[fv-az585-767:08065] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9e07a29e40]
[fv-az585-767:08065] [11] plumed_master(+0x14eb5)[0x558a26834eb5]
[fv-az585-767:08065] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az585-767:08064] *** Process received signal ***
[fv-az585-767:08064] Signal: Aborted (6)
[fv-az585-767:08064] Signal code:  (-6)
[fv-az585-767:08064] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fed38242520]
[fv-az585-767:08064] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fed382969fc]
[fv-az585-767:08064] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fed38242476]
[fv-az585-767:08064] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fed382287f3]
[fv-az585-767:08064] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fed386a2b9e]
[fv-az585-767:08064] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fed386ae20c]
[fv-az585-767:08064] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fed386ae277]
[fv-az585-767:08064] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fed386ae52b]
[fv-az585-767:08064] [ 8] plumed_master(+0x14254)[0x55bf02b73254]
[fv-az585-767:08064] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fed38229d90]
[fv-az585-767:08064] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fed38229e40]
[fv-az585-767:08064] [11] plumed_master(+0x14eb5)[0x55bf02b73eb5]
[fv-az585-767:08064] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az585-767 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
