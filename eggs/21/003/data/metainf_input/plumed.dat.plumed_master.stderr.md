**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmberfyhpb9w:11991] *** Process received signal ***
[pkrvmberfyhpb9w:11991] Signal: Aborted (6)
[pkrvmberfyhpb9w:11991] Signal code:  (-6)
[pkrvmberfyhpb9w:11991] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efeed845330]
[pkrvmberfyhpb9w:11991] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efeed89eb2c]
[pkrvmberfyhpb9w:11991] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efeed84527e]
[pkrvmberfyhpb9w:11991] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efeed8288ff]
[pkrvmberfyhpb9w:11991] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efeedca5ff5]
[pkrvmberfyhpb9w:11991] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efeedcbb0da]
[pkrvmberfyhpb9w:11991] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efeedca5a55]
[pkrvmberfyhpb9w:11991] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efeedca5a6f]
[pkrvmberfyhpb9w:11991] [ 8] plumed_master(+0x146dd)[0x55e77ad9d6dd]
[pkrvmberfyhpb9w:11991] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efeed82a1ca]
[pkrvmberfyhpb9w:11991] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efeed82a28b]
[pkrvmberfyhpb9w:11991] [11] plumed_master(+0x15365)[0x55e77ad9e365]
[pkrvmberfyhpb9w:11991] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmberfyhpb9w:11992] *** Process received signal ***
[pkrvmberfyhpb9w:11992] Signal: Aborted (6)
[pkrvmberfyhpb9w:11992] Signal code:  (-6)
[pkrvmberfyhpb9w:11992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d72645330]
[pkrvmberfyhpb9w:11992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d7269eb2c]
[pkrvmberfyhpb9w:11992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d7264527e]
[pkrvmberfyhpb9w:11992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d726288ff]
[pkrvmberfyhpb9w:11992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d72aa5ff5]
[pkrvmberfyhpb9w:11992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d72abb0da]
[pkrvmberfyhpb9w:11992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d72aa5a55]
[pkrvmberfyhpb9w:11992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d72aa5a6f]
[pkrvmberfyhpb9w:11992] [ 8] plumed_master(+0x146dd)[0x55e24e1ff6dd]
[pkrvmberfyhpb9w:11992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d7262a1ca]
[pkrvmberfyhpb9w:11992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d7262a28b]
[pkrvmberfyhpb9w:11992] [11] plumed_master(+0x15365)[0x55e24e200365]
[pkrvmberfyhpb9w:11992] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmberfyhpb9w exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
