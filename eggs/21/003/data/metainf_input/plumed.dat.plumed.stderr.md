**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1215-453:08979] *** Process received signal ***
[fv-az1215-453:08979] Signal: Aborted (6)
[fv-az1215-453:08979] Signal code:  (-6)
[fv-az1215-453:08979] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7efd56242520]
[fv-az1215-453:08979] [ 1] terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
/lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7efd562969fc]
[fv-az1215-453:08979] [ 2]   what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
/lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7efd56242476]
[fv-az1215-453:08979] [ 3] [fv-az1215-453:08978] *** Process received signal ***
[fv-az1215-453:08978] Signal: Aborted (6)
[fv-az1215-453:08978] Signal code:  (-6)
/lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7efd562287f3]
[fv-az1215-453:08979] [ 4] [fv-az1215-453:08978] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2156242520]
[fv-az1215-453:08978] [ 1] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7efd566a2b9e]
[fv-az1215-453:08979] [ 5] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f21562969fc]
[fv-az1215-453:08978] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2156242476]
[fv-az1215-453:08978] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7efd566ae20c]
[fv-az1215-453:08979] [ 6] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f21562287f3]
[fv-az1215-453:08978] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7efd566ae277]
[fv-az1215-453:08979] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f21566a2b9e]
[fv-az1215-453:08978] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7efd566ae52b]
[fv-az1215-453:08979] [ 8] plumed(+0x12f48)[0x56186999af48]
/lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f21566ae20c]
[fv-az1215-453:08978] [ 6] [fv-az1215-453:08979] [ 9] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f21566ae277]
[fv-az1215-453:08978] [ 7] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7efd56229d90]
[fv-az1215-453:08979] [10] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f21566ae52b]
[fv-az1215-453:08978] [ 8] plumed(+0x12f48)[0x5635d2d34f48]
[fv-az1215-453:08978] [ 9] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7efd56229e40]
[fv-az1215-453:08979] [11] plumed(+0x131e5)[0x56186999b1e5]
[fv-az1215-453:08979] *** End of error message ***
/lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2156229d90]
[fv-az1215-453:08978] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2156229e40]
[fv-az1215-453:08978] [11] plumed(+0x131e5)[0x5635d2d351e5]
[fv-az1215-453:08978] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1215-453 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
