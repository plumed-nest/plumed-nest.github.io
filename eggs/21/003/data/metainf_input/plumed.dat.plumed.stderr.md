**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680

[fv-az585-767:08052] *** Process received signal ***
[fv-az585-767:08052] Signal: Aborted (6)
[fv-az585-767:08052] Signal code:  (-6)
[fv-az585-767:08052] [fv-az585-767:08053] *** Process received signal ***
[fv-az585-767:08053] Signal: Aborted (6)
[fv-az585-767:08053] Signal code:  (-6)
[fv-az585-767:08053] [ 0] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa531642520]
[fv-az585-767:08052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f99a1242520]
[fv-az585-767:08053] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa5316969fc]
[fv-az585-767:08052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f99a12969fc]
[fv-az585-767:08053] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa531642476]
[fv-az585-767:08052] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa5316287f3]
[fv-az585-767:08052] [ 4] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f99a1242476]
[fv-az585-767:08053] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa531aa2b9e]
[fv-az585-767:08052] [ 5] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f99a12287f3]
[fv-az585-767:08053] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa531aae20c]
[fv-az585-767:08052] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f99a16a2b9e]
[fv-az585-767:08053] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa531aae277]
[fv-az585-767:08052] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa531aae52b]
[fv-az585-767:08052] [ 8] plumed(+0x14254)[0x556f0d1fa254]
[fv-az585-767:08052] [ 9] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f99a16ae20c]
[fv-az585-767:08053] [ 6] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa531629d90]
[fv-az585-767:08052] [10] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f99a16ae277]
[fv-az585-767:08053] [ 7] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa531629e40]
[fv-az585-767:08052] [11] plumed(+0x14eb5)[0x556f0d1faeb5]
[fv-az585-767:08052] *** End of error message ***
/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f99a16ae52b]
[fv-az585-767:08053] [ 8] plumed(+0x14254)[0x562c61ba1254]
[fv-az585-767:08053] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f99a1229d90]
[fv-az585-767:08053] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f99a1229e40]
[fv-az585-767:08053] [11] plumed(+0x14eb5)[0x562c61ba1eb5]
[fv-az585-767:08053] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az585-767 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
