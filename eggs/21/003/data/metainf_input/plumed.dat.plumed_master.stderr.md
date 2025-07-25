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
[pkrvmpptgkbjq6m:11488] *** Process received signal ***
[pkrvmpptgkbjq6m:11488] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11488] Signal code:  (-6)
[pkrvmpptgkbjq6m:11488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3c25a45330]
[pkrvmpptgkbjq6m:11488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3c25a9eb2c]
[pkrvmpptgkbjq6m:11488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3c25a4527e]
[pkrvmpptgkbjq6m:11488] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3c25a288ff]
[pkrvmpptgkbjq6m:11488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3c25ea5ff5]
[pkrvmpptgkbjq6m:11488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3c25ebb0da]
[pkrvmpptgkbjq6m:11488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3c25ea5a55]
[pkrvmpptgkbjq6m:11488] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3c25ea5a6f]
[pkrvmpptgkbjq6m:11488] [ 8] plumed_master(+0x146dd)[0x5635fb6b96dd]
[pkrvmpptgkbjq6m:11488] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3c25a2a1ca]
[pkrvmpptgkbjq6m:11488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3c25a2a28b]
[pkrvmpptgkbjq6m:11488] [11] plumed_master(+0x15365)[0x5635fb6ba365]
[pkrvmpptgkbjq6m:11488] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmpptgkbjq6m:11487] *** Process received signal ***
[pkrvmpptgkbjq6m:11487] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11487] Signal code:  (-6)
[pkrvmpptgkbjq6m:11487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f783e845330]
[pkrvmpptgkbjq6m:11487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f783e89eb2c]
[pkrvmpptgkbjq6m:11487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f783e84527e]
[pkrvmpptgkbjq6m:11487] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f783e8288ff]
[pkrvmpptgkbjq6m:11487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f783eca5ff5]
[pkrvmpptgkbjq6m:11487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f783ecbb0da]
[pkrvmpptgkbjq6m:11487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f783eca5a55]
[pkrvmpptgkbjq6m:11487] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f783eca5a6f]
[pkrvmpptgkbjq6m:11487] [ 8] plumed_master(+0x146dd)[0x563b922e16dd]
[pkrvmpptgkbjq6m:11487] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f783e82a1ca]
[pkrvmpptgkbjq6m:11487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f783e82a28b]
[pkrvmpptgkbjq6m:11487] [11] plumed_master(+0x15365)[0x563b922e2365]
[pkrvmpptgkbjq6m:11487] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node pkrvmpptgkbjq6m exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
