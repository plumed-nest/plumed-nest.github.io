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
[fv-az1344-582:65604] *** Process received signal ***
[fv-az1344-582:65604] Signal: Aborted (6)
[fv-az1344-582:65604] Signal code:  (-6)
[fv-az1344-582:65604] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1ff9c45330]
[fv-az1344-582:65604] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1ff9c9eb2c]
[fv-az1344-582:65604] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1ff9c4527e]
[fv-az1344-582:65604] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1ff9c288ff]
[fv-az1344-582:65604] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ffa0a5ff5]
[fv-az1344-582:65604] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ffa0bb0da]
[fv-az1344-582:65604] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ffa0a5a55]
[fv-az1344-582:65604] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ffa0a5a6f]
[fv-az1344-582:65604] [ 8] plumed_master(+0x146dd)[0x5588198946dd]
[fv-az1344-582:65604] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1ff9c2a1ca]
[fv-az1344-582:65604] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1ff9c2a28b]
[fv-az1344-582:65604] [11] plumed_master(+0x15365)[0x558819895365]
[fv-az1344-582:65604] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1344-582:65605] *** Process received signal ***
[fv-az1344-582:65605] Signal: Aborted (6)
[fv-az1344-582:65605] Signal code:  (-6)
[fv-az1344-582:65605] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71e9645330]
[fv-az1344-582:65605] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71e969eb2c]
[fv-az1344-582:65605] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71e964527e]
[fv-az1344-582:65605] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71e96288ff]
[fv-az1344-582:65605] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71e9aa5ff5]
[fv-az1344-582:65605] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71e9abb0da]
[fv-az1344-582:65605] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71e9aa5a55]
[fv-az1344-582:65605] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71e9aa5a6f]
[fv-az1344-582:65605] [ 8] plumed_master(+0x146dd)[0x560081d716dd]
[fv-az1344-582:65605] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71e962a1ca]
[fv-az1344-582:65605] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71e962a28b]
[fv-az1344-582:65605] [11] plumed_master(+0x15365)[0x560081d72365]
[fv-az1344-582:65605] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1344-582 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
