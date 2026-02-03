**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmkj6or:08089] *** Process received signal ***
[runnervmkj6or:08089] Signal: Aborted (6)
[runnervmkj6or:08089] Signal code:  (-6)
[runnervmkj6or:08089] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4690a45330]
[runnervmkj6or:08089] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4690a9eb2c]
[runnervmkj6or:08089] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4690a4527e]
[runnervmkj6or:08089] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4690a288ff]
[runnervmkj6or:08089] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4690ea5ff5]
[runnervmkj6or:08089] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4690ebb0da]
[runnervmkj6or:08089] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4690ea5a55]
[runnervmkj6or:08089] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4690ea5a6f]
[runnervmkj6or:08089] [ 8] plumed_master(+0x146dd)[0x56523426c6dd]
[runnervmkj6or:08089] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4690a2a1ca]
[runnervmkj6or:08089] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4690a2a28b]
[runnervmkj6or:08089] [11] plumed_master(+0x15365)[0x56523426d365]
[runnervmkj6or:08089] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmkj6or:08088] *** Process received signal ***
[runnervmkj6or:08088] Signal: Aborted (6)
[runnervmkj6or:08088] Signal code:  (-6)
[runnervmkj6or:08088] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6dda445330]
[runnervmkj6or:08088] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6dda49eb2c]
[runnervmkj6or:08088] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6dda44527e]
[runnervmkj6or:08088] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6dda4288ff]
[runnervmkj6or:08088] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6dda8a5ff5]
[runnervmkj6or:08088] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6dda8bb0da]
[runnervmkj6or:08088] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6dda8a5a55]
[runnervmkj6or:08088] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6dda8a5a6f]
[runnervmkj6or:08088] [ 8] plumed_master(+0x146dd)[0x55ef8fd1b6dd]
[runnervmkj6or:08088] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6dda42a1ca]
[runnervmkj6or:08088] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6dda42a28b]
[runnervmkj6or:08088] [11] plumed_master(+0x15365)[0x55ef8fd1c365]
[runnervmkj6or:08088] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmkj6or exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
