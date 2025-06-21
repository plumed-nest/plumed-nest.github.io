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
[pkrvmxyh4eaekms:09643] *** Process received signal ***
[pkrvmxyh4eaekms:09643] Signal: Aborted (6)
[pkrvmxyh4eaekms:09643] Signal code:  (-6)
[pkrvmxyh4eaekms:09643] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd263c45330]
[pkrvmxyh4eaekms:09643] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd263c9eb2c]
[pkrvmxyh4eaekms:09643] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd263c4527e]
[pkrvmxyh4eaekms:09643] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd263c288ff]
[pkrvmxyh4eaekms:09643] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2640a5ff5]
[pkrvmxyh4eaekms:09643] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2640bb0da]
[pkrvmxyh4eaekms:09643] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2640a5a55]
[pkrvmxyh4eaekms:09643] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2640a5a6f]
[pkrvmxyh4eaekms:09643] [ 8] plumed(+0x146dd)[0x561aff6176dd]
[pkrvmxyh4eaekms:09643] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd263c2a1ca]
[pkrvmxyh4eaekms:09643] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd263c2a28b]
[pkrvmxyh4eaekms:09643] [11] plumed(+0x15365)[0x561aff618365]
[pkrvmxyh4eaekms:09643] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmxyh4eaekms:09644] *** Process received signal ***
[pkrvmxyh4eaekms:09644] Signal: Aborted (6)
[pkrvmxyh4eaekms:09644] Signal code:  (-6)
[pkrvmxyh4eaekms:09644] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f084e445330]
[pkrvmxyh4eaekms:09644] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f084e49eb2c]
[pkrvmxyh4eaekms:09644] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f084e44527e]
[pkrvmxyh4eaekms:09644] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f084e4288ff]
[pkrvmxyh4eaekms:09644] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f084e8a5ff5]
[pkrvmxyh4eaekms:09644] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f084e8bb0da]
[pkrvmxyh4eaekms:09644] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f084e8a5a55]
[pkrvmxyh4eaekms:09644] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f084e8a5a6f]
[pkrvmxyh4eaekms:09644] [ 8] plumed(+0x146dd)[0x558d9c5e86dd]
[pkrvmxyh4eaekms:09644] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f084e42a1ca]
[pkrvmxyh4eaekms:09644] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f084e42a28b]
[pkrvmxyh4eaekms:09644] [11] plumed(+0x15365)[0x558d9c5e9365]
[pkrvmxyh4eaekms:09644] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmxyh4eaekms exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
