**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmq0rgcvqdmg:11229] *** Process received signal ***
[pkrvmq0rgcvqdmg:11229] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11229] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11229] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa319845330]
[pkrvmq0rgcvqdmg:11229] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa31989eb2c]
[pkrvmq0rgcvqdmg:11229] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa31984527e]
[pkrvmq0rgcvqdmg:11229] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3198288ff]
[pkrvmq0rgcvqdmg:11229] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa319ca5ff5]
[pkrvmq0rgcvqdmg:11229] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa319cbb0da]
[pkrvmq0rgcvqdmg:11229] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa319ca5a55]
[pkrvmq0rgcvqdmg:11229] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa319ca5a6f]
[pkrvmq0rgcvqdmg:11229] [ 8] plumed_master(+0x146dd)[0x5581ff7b66dd]
[pkrvmq0rgcvqdmg:11229] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa31982a1ca]
[pkrvmq0rgcvqdmg:11229] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa31982a28b]
[pkrvmq0rgcvqdmg:11229] [11] plumed_master(+0x15365)[0x5581ff7b7365]
[pkrvmq0rgcvqdmg:11229] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmq0rgcvqdmg:11230] *** Process received signal ***
[pkrvmq0rgcvqdmg:11230] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11230] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11230] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff4bc645330]
[pkrvmq0rgcvqdmg:11230] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff4bc69eb2c]
[pkrvmq0rgcvqdmg:11230] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff4bc64527e]
[pkrvmq0rgcvqdmg:11230] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff4bc6288ff]
[pkrvmq0rgcvqdmg:11230] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4bcaa5ff5]
[pkrvmq0rgcvqdmg:11230] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4bcabb0da]
[pkrvmq0rgcvqdmg:11230] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4bcaa5a55]
[pkrvmq0rgcvqdmg:11230] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4bcaa5a6f]
[pkrvmq0rgcvqdmg:11230] [ 8] plumed_master(+0x146dd)[0x563f63e2e6dd]
[pkrvmq0rgcvqdmg:11230] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff4bc62a1ca]
[pkrvmq0rgcvqdmg:11230] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff4bc62a28b]
[pkrvmq0rgcvqdmg:11230] [11] plumed_master(+0x15365)[0x563f63e2f365]
[pkrvmq0rgcvqdmg:11230] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmq0rgcvqdmg exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
