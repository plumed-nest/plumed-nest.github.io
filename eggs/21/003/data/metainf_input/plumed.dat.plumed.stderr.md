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
[fv-az1719-82:68187] *** Process received signal ***
[fv-az1719-82:68187] Signal: Aborted (6)
[fv-az1719-82:68187] Signal code:  (-6)
[fv-az1719-82:68187] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1849a45330]
[fv-az1719-82:68187] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1849a9eb2c]
[fv-az1719-82:68187] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1849a4527e]
[fv-az1719-82:68187] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1849a288ff]
[fv-az1719-82:68187] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1849ea5ff5]
[fv-az1719-82:68187] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1849ebb0da]
[fv-az1719-82:68187] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1849ea5a55]
[fv-az1719-82:68187] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1849ea5a6f]
[fv-az1719-82:68187] [ 8] plumed(+0x146dd)[0x556410d436dd]
[fv-az1719-82:68187] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1849a2a1ca]
[fv-az1719-82:68187] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1849a2a28b]
[fv-az1719-82:68187] [11] plumed(+0x15365)[0x556410d44365]
[fv-az1719-82:68187] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1719-82:68186] *** Process received signal ***
[fv-az1719-82:68186] Signal: Aborted (6)
[fv-az1719-82:68186] Signal code:  (-6)
[fv-az1719-82:68186] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f563c245330]
[fv-az1719-82:68186] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f563c29eb2c]
[fv-az1719-82:68186] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f563c24527e]
[fv-az1719-82:68186] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f563c2288ff]
[fv-az1719-82:68186] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f563c6a5ff5]
[fv-az1719-82:68186] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f563c6bb0da]
[fv-az1719-82:68186] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f563c6a5a55]
[fv-az1719-82:68186] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f563c6a5a6f]
[fv-az1719-82:68186] [ 8] plumed(+0x146dd)[0x55af3abe16dd]
[fv-az1719-82:68186] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f563c22a1ca]
[fv-az1719-82:68186] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f563c22a28b]
[fv-az1719-82:68186] [11] plumed(+0x15365)[0x55af3abe2365]
[fv-az1719-82:68186] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1719-82 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
