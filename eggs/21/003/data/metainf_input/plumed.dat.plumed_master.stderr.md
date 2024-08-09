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
[fv-az1530-541:08962] *** Process received signal ***
[fv-az1530-541:08962] Signal: Aborted (6)
[fv-az1530-541:08962] Signal code:  (-6)
[fv-az1530-541:08962] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5b05a42520]
[fv-az1530-541:08962] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5b05a969fc]
[fv-az1530-541:08962] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5b05a42476]
[fv-az1530-541:08962] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5b05a287f3]
[fv-az1530-541:08962] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5b05ea2b9e]
[fv-az1530-541:08962] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5b05eae20c]
[fv-az1530-541:08962] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5b05eae277]
[fv-az1530-541:08962] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5b05eae52b]
[fv-az1530-541:08962] [ 8] plumed_master(+0x14274)[0x55e1faa50274]
[fv-az1530-541:08962] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5b05a29d90]
[fv-az1530-541:08962] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5b05a29e40]
[fv-az1530-541:08962] [11] plumed_master(+0x14ed5)[0x55e1faa50ed5]
[fv-az1530-541:08962] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1530-541:08963] *** Process received signal ***
[fv-az1530-541:08963] Signal: Aborted (6)
[fv-az1530-541:08963] Signal code:  (-6)
[fv-az1530-541:08963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f79bdc42520]
[fv-az1530-541:08963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f79bdc969fc]
[fv-az1530-541:08963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f79bdc42476]
[fv-az1530-541:08963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f79bdc287f3]
[fv-az1530-541:08963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f79be0a2b9e]
[fv-az1530-541:08963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f79be0ae20c]
[fv-az1530-541:08963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f79be0ae277]
[fv-az1530-541:08963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f79be0ae52b]
[fv-az1530-541:08963] [ 8] plumed_master(+0x14274)[0x562147e1a274]
[fv-az1530-541:08963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f79bdc29d90]
[fv-az1530-541:08963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f79bdc29e40]
[fv-az1530-541:08963] [11] plumed_master(+0x14ed5)[0x562147e1aed5]
[fv-az1530-541:08963] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1530-541 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
