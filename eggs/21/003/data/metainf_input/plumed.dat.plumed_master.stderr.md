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
[pkrvmxyh4eaekms:09680] *** Process received signal ***
[pkrvmxyh4eaekms:09680] Signal: Aborted (6)
[pkrvmxyh4eaekms:09680] Signal code:  (-6)
[pkrvmxyh4eaekms:09680] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb826645330]
[pkrvmxyh4eaekms:09680] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb82669eb2c]
[pkrvmxyh4eaekms:09680] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb82664527e]
[pkrvmxyh4eaekms:09680] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8266288ff]
[pkrvmxyh4eaekms:09680] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb826aa5ff5]
[pkrvmxyh4eaekms:09680] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb826abb0da]
[pkrvmxyh4eaekms:09680] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb826aa5a55]
[pkrvmxyh4eaekms:09680] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb826aa5a6f]
[pkrvmxyh4eaekms:09680] [ 8] plumed_master(+0x146dd)[0x55a01e4346dd]
[pkrvmxyh4eaekms:09680] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb82662a1ca]
[pkrvmxyh4eaekms:09680] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb82662a28b]
[pkrvmxyh4eaekms:09680] [11] plumed_master(+0x15365)[0x55a01e435365]
[pkrvmxyh4eaekms:09680] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmxyh4eaekms:09679] *** Process received signal ***
[pkrvmxyh4eaekms:09679] Signal: Aborted (6)
[pkrvmxyh4eaekms:09679] Signal code:  (-6)
[pkrvmxyh4eaekms:09679] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fabcd245330]
[pkrvmxyh4eaekms:09679] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fabcd29eb2c]
[pkrvmxyh4eaekms:09679] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fabcd24527e]
[pkrvmxyh4eaekms:09679] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fabcd2288ff]
[pkrvmxyh4eaekms:09679] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fabcd6a5ff5]
[pkrvmxyh4eaekms:09679] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fabcd6bb0da]
[pkrvmxyh4eaekms:09679] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fabcd6a5a55]
[pkrvmxyh4eaekms:09679] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fabcd6a5a6f]
[pkrvmxyh4eaekms:09679] [ 8] plumed_master(+0x146dd)[0x55f001cd36dd]
[pkrvmxyh4eaekms:09679] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fabcd22a1ca]
[pkrvmxyh4eaekms:09679] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fabcd22a28b]
[pkrvmxyh4eaekms:09679] [11] plumed_master(+0x15365)[0x55f001cd4365]
[pkrvmxyh4eaekms:09679] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node pkrvmxyh4eaekms exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
