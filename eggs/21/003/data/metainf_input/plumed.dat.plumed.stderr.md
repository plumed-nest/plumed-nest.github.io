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
[pkrvmpptgkbjq6m:11450] *** Process received signal ***
[pkrvmpptgkbjq6m:11450] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11450] Signal code:  (-6)
[pkrvmpptgkbjq6m:11450] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f61e2645330]
[pkrvmpptgkbjq6m:11450] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f61e269eb2c]
[pkrvmpptgkbjq6m:11450] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f61e264527e]
[pkrvmpptgkbjq6m:11450] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f61e26288ff]
[pkrvmpptgkbjq6m:11450] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f61e2aa5ff5]
[pkrvmpptgkbjq6m:11450] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f61e2abb0da]
[pkrvmpptgkbjq6m:11450] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f61e2aa5a55]
[pkrvmpptgkbjq6m:11450] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f61e2aa5a6f]
[pkrvmpptgkbjq6m:11450] [ 8] plumed(+0x146dd)[0x558ab387a6dd]
[pkrvmpptgkbjq6m:11450] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f61e262a1ca]
[pkrvmpptgkbjq6m:11450] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f61e262a28b]
[pkrvmpptgkbjq6m:11450] [11] plumed(+0x15365)[0x558ab387b365]
[pkrvmpptgkbjq6m:11450] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmpptgkbjq6m:11451] *** Process received signal ***
[pkrvmpptgkbjq6m:11451] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11451] Signal code:  (-6)
[pkrvmpptgkbjq6m:11451] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff80a445330]
[pkrvmpptgkbjq6m:11451] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff80a49eb2c]
[pkrvmpptgkbjq6m:11451] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff80a44527e]
[pkrvmpptgkbjq6m:11451] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff80a4288ff]
[pkrvmpptgkbjq6m:11451] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff80a8a5ff5]
[pkrvmpptgkbjq6m:11451] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff80a8bb0da]
[pkrvmpptgkbjq6m:11451] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff80a8a5a55]
[pkrvmpptgkbjq6m:11451] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff80a8a5a6f]
[pkrvmpptgkbjq6m:11451] [ 8] plumed(+0x146dd)[0x5602538d36dd]
[pkrvmpptgkbjq6m:11451] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff80a42a1ca]
[pkrvmpptgkbjq6m:11451] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff80a42a28b]
[pkrvmpptgkbjq6m:11451] [11] plumed(+0x15365)[0x5602538d4365]
[pkrvmpptgkbjq6m:11451] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmpptgkbjq6m exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
