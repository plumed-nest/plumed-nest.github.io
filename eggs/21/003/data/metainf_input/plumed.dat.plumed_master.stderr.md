**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1200-632:72272] *** Process received signal ***
[fv-az1200-632:72272] Signal: Aborted (6)
[fv-az1200-632:72272] Signal code:  (-6)
[fv-az1200-632:72272] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3fe1e42520]
[fv-az1200-632:72272] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3fe1e969fc]
[fv-az1200-632:72272] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3fe1e42476]
[fv-az1200-632:72272] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3fe1e287f3]
[fv-az1200-632:72272] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f3fe22a4f26]
[fv-az1200-632:72272] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f3fe22b6d9c]
[fv-az1200-632:72272] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f3fe22b6e07]
[fv-az1200-632:72272] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3fe22b70bb]
[fv-az1200-632:72272] [ 8] plumed_master(+0x12e7f)[0x559715030e7f]
[fv-az1200-632:72272] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3fe1e29d90]
[fv-az1200-632:72272] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3fe1e29e40]
[fv-az1200-632:72272] [11] plumed_master(+0x13115)[0x559715031115]
[fv-az1200-632:72272] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1200-632:72271] *** Process received signal ***
[fv-az1200-632:72271] Signal: Aborted (6)
[fv-az1200-632:72271] Signal code:  (-6)
[fv-az1200-632:72271] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f96f0c42520]
[fv-az1200-632:72271] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f96f0c969fc]
[fv-az1200-632:72271] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f96f0c42476]
[fv-az1200-632:72271] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f96f0c287f3]
[fv-az1200-632:72271] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f96f10a4f26]
[fv-az1200-632:72271] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f96f10b6d9c]
[fv-az1200-632:72271] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f96f10b6e07]
[fv-az1200-632:72271] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f96f10b70bb]
[fv-az1200-632:72271] [ 8] plumed_master(+0x12e7f)[0x55b67df03e7f]
[fv-az1200-632:72271] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f96f0c29d90]
[fv-az1200-632:72271] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f96f0c29e40]
[fv-az1200-632:72271] [11] plumed_master(+0x13115)[0x55b67df04115]
[fv-az1200-632:72271] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1200-632 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
