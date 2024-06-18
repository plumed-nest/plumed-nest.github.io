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
[fv-az1215-453:08991] *** Process received signal ***
[fv-az1215-453:08991] Signal: Aborted (6)
[fv-az1215-453:08991] Signal code:  (-6)
[fv-az1215-453:08991] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8173442520]
[fv-az1215-453:08991] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f81734969fc]
[fv-az1215-453:08991] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8173442476]
[fv-az1215-453:08991] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f81734287f3]
[fv-az1215-453:08991] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f81738a2b9e]
[fv-az1215-453:08991] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f81738ae20c]
[fv-az1215-453:08991] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f81738ae277]
[fv-az1215-453:08991] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f81738ae52b]
[fv-az1215-453:08991] [ 8] plumed_master(+0x14274)[0x558533a6d274]
[fv-az1215-453:08991] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8173429d90]
[fv-az1215-453:08991] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8173429e40]
[fv-az1215-453:08991] [11] plumed_master(+0x14ed5)[0x558533a6ded5]
[fv-az1215-453:08991] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1215-453:08990] *** Process received signal ***
[fv-az1215-453:08990] Signal: Aborted (6)
[fv-az1215-453:08990] Signal code:  (-6)
[fv-az1215-453:08990] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6a3b842520]
[fv-az1215-453:08990] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6a3b8969fc]
[fv-az1215-453:08990] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6a3b842476]
[fv-az1215-453:08990] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6a3b8287f3]
[fv-az1215-453:08990] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6a3bca2b9e]
[fv-az1215-453:08990] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6a3bcae20c]
[fv-az1215-453:08990] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6a3bcae277]
[fv-az1215-453:08990] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6a3bcae52b]
[fv-az1215-453:08990] [ 8] plumed_master(+0x14274)[0x564979ea0274]
[fv-az1215-453:08990] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6a3b829d90]
[fv-az1215-453:08990] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6a3b829e40]
[fv-az1215-453:08990] [11] plumed_master(+0x14ed5)[0x564979ea0ed5]
[fv-az1215-453:08990] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1215-453 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
