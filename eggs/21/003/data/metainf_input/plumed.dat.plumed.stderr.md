**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmberfyhpb9w:11957] *** Process received signal ***
[pkrvmberfyhpb9w:11957] Signal: Aborted (6)
[pkrvmberfyhpb9w:11957] Signal code:  (-6)
[pkrvmberfyhpb9w:11957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9800645330]
[pkrvmberfyhpb9w:11957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f980069eb2c]
[pkrvmberfyhpb9w:11957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f980064527e]
[pkrvmberfyhpb9w:11957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98006288ff]
[pkrvmberfyhpb9w:11957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9800aa5ff5]
[pkrvmberfyhpb9w:11957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9800abb0da]
[pkrvmberfyhpb9w:11957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9800aa5a55]
[pkrvmberfyhpb9w:11957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9800aa5a6f]
[pkrvmberfyhpb9w:11957] [ 8] plumed(+0x146dd)[0x557fd4d616dd]
[pkrvmberfyhpb9w:11957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f980062a1ca]
[pkrvmberfyhpb9w:11957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f980062a28b]
[pkrvmberfyhpb9w:11957] [11] plumed(+0x15365)[0x557fd4d62365]
[pkrvmberfyhpb9w:11957] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmberfyhpb9w:11958] *** Process received signal ***
[pkrvmberfyhpb9w:11958] Signal: Aborted (6)
[pkrvmberfyhpb9w:11958] Signal code:  (-6)
[pkrvmberfyhpb9w:11958] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb7e9445330]
[pkrvmberfyhpb9w:11958] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb7e949eb2c]
[pkrvmberfyhpb9w:11958] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb7e944527e]
[pkrvmberfyhpb9w:11958] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7e94288ff]
[pkrvmberfyhpb9w:11958] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7e98a5ff5]
[pkrvmberfyhpb9w:11958] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7e98bb0da]
[pkrvmberfyhpb9w:11958] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7e98a5a55]
[pkrvmberfyhpb9w:11958] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7e98a5a6f]
[pkrvmberfyhpb9w:11958] [ 8] plumed(+0x146dd)[0x5578025bf6dd]
[pkrvmberfyhpb9w:11958] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb7e942a1ca]
[pkrvmberfyhpb9w:11958] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb7e942a28b]
[pkrvmberfyhpb9w:11958] [11] plumed(+0x15365)[0x5578025c0365]
[pkrvmberfyhpb9w:11958] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmberfyhpb9w exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
