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
[fv-az1530-541:08951] *** Process received signal ***
[fv-az1530-541:08951] Signal: Aborted (6)
[fv-az1530-541:08951] Signal code:  (-6)
[fv-az1530-541:08951] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fcec5442520]
[fv-az1530-541:08951] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fcec54969fc]
[fv-az1530-541:08951] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fcec5442476]
[fv-az1530-541:08951] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fcec54287f3]
[fv-az1530-541:08951] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fcec58a2b9e]
[fv-az1530-541:08951] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fcec58ae20c]
[fv-az1530-541:08951] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fcec58ae277]
[fv-az1530-541:08951] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fcec58ae52b]
[fv-az1530-541:08951] [ 8] plumed(+0x12f48)[0x563a1a45ff48]
[fv-az1530-541:08951] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fcec5429d90]
[fv-az1530-541:08951] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fcec5429e40]
[fv-az1530-541:08951] [11] plumed(+0x131e5)[0x563a1a4601e5]
[fv-az1530-541:08951] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1530-541:08950] *** Process received signal ***
[fv-az1530-541:08950] Signal: Aborted (6)
[fv-az1530-541:08950] Signal code:  (-6)
[fv-az1530-541:08950] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f656a442520]
[fv-az1530-541:08950] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f656a4969fc]
[fv-az1530-541:08950] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f656a442476]
[fv-az1530-541:08950] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f656a4287f3]
[fv-az1530-541:08950] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f656a8a2b9e]
[fv-az1530-541:08950] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f656a8ae20c]
[fv-az1530-541:08950] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f656a8ae277]
[fv-az1530-541:08950] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f656a8ae52b]
[fv-az1530-541:08950] [ 8] plumed(+0x12f48)[0x562d15a3bf48]
[fv-az1530-541:08950] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f656a429d90]
[fv-az1530-541:08950] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f656a429e40]
[fv-az1530-541:08950] [11] plumed(+0x131e5)[0x562d15a3c1e5]
[fv-az1530-541:08950] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1530-541 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
