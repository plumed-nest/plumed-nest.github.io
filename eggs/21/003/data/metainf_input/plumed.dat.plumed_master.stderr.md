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
[pkrvmf6wy0o8zjz:66240] *** Process received signal ***
[pkrvmf6wy0o8zjz:66240] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66240] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66240] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a69e45330]
[pkrvmf6wy0o8zjz:66240] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a69e9eb2c]
[pkrvmf6wy0o8zjz:66240] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a69e4527e]
[pkrvmf6wy0o8zjz:66240] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a69e288ff]
[pkrvmf6wy0o8zjz:66240] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a6a2a5ff5]
[pkrvmf6wy0o8zjz:66240] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a6a2bb0da]
[pkrvmf6wy0o8zjz:66240] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a6a2a5a55]
[pkrvmf6wy0o8zjz:66240] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a6a2a5a6f]
[pkrvmf6wy0o8zjz:66240] [ 8] plumed_master(+0x146dd)[0x55f70b0076dd]
[pkrvmf6wy0o8zjz:66240] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a69e2a1ca]
[pkrvmf6wy0o8zjz:66240] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a69e2a28b]
[pkrvmf6wy0o8zjz:66240] [11] plumed_master(+0x15365)[0x55f70b008365]
[pkrvmf6wy0o8zjz:66240] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmf6wy0o8zjz:66239] *** Process received signal ***
[pkrvmf6wy0o8zjz:66239] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66239] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66239] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f15645330]
[pkrvmf6wy0o8zjz:66239] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f1569eb2c]
[pkrvmf6wy0o8zjz:66239] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f1564527e]
[pkrvmf6wy0o8zjz:66239] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f156288ff]
[pkrvmf6wy0o8zjz:66239] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f15aa5ff5]
[pkrvmf6wy0o8zjz:66239] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f15abb0da]
[pkrvmf6wy0o8zjz:66239] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f15aa5a55]
[pkrvmf6wy0o8zjz:66239] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f15aa5a6f]
[pkrvmf6wy0o8zjz:66239] [ 8] plumed_master(+0x146dd)[0x55f6dd1786dd]
[pkrvmf6wy0o8zjz:66239] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f1562a1ca]
[pkrvmf6wy0o8zjz:66239] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f1562a28b]
[pkrvmf6wy0o8zjz:66239] [11] plumed_master(+0x15365)[0x55f6dd179365]
[pkrvmf6wy0o8zjz:66239] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmf6wy0o8zjz exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
