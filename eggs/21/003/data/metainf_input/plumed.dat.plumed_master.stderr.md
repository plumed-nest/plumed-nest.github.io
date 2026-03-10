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
[runnervm0kj6c:09111] *** Process received signal ***
[runnervm0kj6c:09111] Signal: Aborted (6)
[runnervm0kj6c:09111] Signal code:  (-6)
[runnervm0kj6c:09111] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7eb1445330]
[runnervm0kj6c:09111] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7eb149eb2c]
[runnervm0kj6c:09111] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7eb144527e]
[runnervm0kj6c:09111] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7eb14288ff]
[runnervm0kj6c:09111] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7eb18a5ff5]
[runnervm0kj6c:09111] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7eb18bb0da]
[runnervm0kj6c:09111] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7eb18a5a55]
[runnervm0kj6c:09111] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7eb18a5a6f]
[runnervm0kj6c:09111] [ 8] plumed_master(+0x146dd)[0x55c1e8d6f6dd]
[runnervm0kj6c:09111] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7eb142a1ca]
[runnervm0kj6c:09111] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7eb142a28b]
[runnervm0kj6c:09111] [11] plumed_master(+0x15365)[0x55c1e8d70365]
[runnervm0kj6c:09111] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervm0kj6c:09110] *** Process received signal ***
[runnervm0kj6c:09110] Signal: Aborted (6)
[runnervm0kj6c:09110] Signal code:  (-6)
[runnervm0kj6c:09110] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe650a45330]
[runnervm0kj6c:09110] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe650a9eb2c]
[runnervm0kj6c:09110] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe650a4527e]
[runnervm0kj6c:09110] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe650a288ff]
[runnervm0kj6c:09110] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe650ea5ff5]
[runnervm0kj6c:09110] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe650ebb0da]
[runnervm0kj6c:09110] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe650ea5a55]
[runnervm0kj6c:09110] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe650ea5a6f]
[runnervm0kj6c:09110] [ 8] plumed_master(+0x146dd)[0x55ef6a31e6dd]
[runnervm0kj6c:09110] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe650a2a1ca]
[runnervm0kj6c:09110] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe650a2a28b]
[runnervm0kj6c:09110] [11] plumed_master(+0x15365)[0x55ef6a31f365]
[runnervm0kj6c:09110] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervm0kj6c exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
