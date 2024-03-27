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
[fv-az1200-632:72260] *** Process received signal ***
[fv-az1200-632:72260] Signal: Aborted (6)
[fv-az1200-632:72260] Signal code:  (-6)
[fv-az1200-632:72260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa307042520]
[fv-az1200-632:72260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa3070969fc]
[fv-az1200-632:72260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa307042476]
[fv-az1200-632:72260] [ 3] terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
/lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa3070287f3]
[fv-az1200-632:72260] [ 4] [fv-az1200-632:72259] *** Process received signal ***
[fv-az1200-632:72259] Signal: Aborted (6)
[fv-az1200-632:72259] Signal code:  (-6)
[fv-az1200-632:72259] [ 0] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fa3074a4f26]
[fv-az1200-632:72260] [ 5] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe6df442520]
[fv-az1200-632:72259] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe6df4969fc]
[fv-az1200-632:72259] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe6df442476]
[fv-az1200-632:72259] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fa3074b6d9c]
[fv-az1200-632:72260] [ 6] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe6df4287f3]
[fv-az1200-632:72259] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fa3074b6e07]
[fv-az1200-632:72260] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fe6df8a4f26]
[fv-az1200-632:72259] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fe6df8b6d9c]
[fv-az1200-632:72259] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa3074b70bb]
[fv-az1200-632:72260] [ 8] plumed(+0x12f48)[0x5562f0fa2f48]
[fv-az1200-632:72260] [ 9] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fe6df8b6e07]
[fv-az1200-632:72259] [ 7] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa307029d90]
[fv-az1200-632:72260] [10] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe6df8b70bb]
[fv-az1200-632:72259] [ 8] plumed(+0x12f48)[0x5569618f7f48]
[fv-az1200-632:72259] [ 9] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa307029e40]
[fv-az1200-632:72260] [11] plumed(+0x131e5)[0x5562f0fa31e5]
[fv-az1200-632:72260] *** End of error message ***
/lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe6df429d90]
[fv-az1200-632:72259] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe6df429e40]
[fv-az1200-632:72259] [11] plumed(+0x131e5)[0x5569618f81e5]
[fv-az1200-632:72259] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1200-632 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
