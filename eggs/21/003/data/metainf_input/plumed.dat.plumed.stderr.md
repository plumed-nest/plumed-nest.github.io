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
[fv-az1344-582:65568] *** Process received signal ***
[fv-az1344-582:65568] Signal: Aborted (6)
[fv-az1344-582:65568] Signal code:  (-6)
[fv-az1344-582:65568] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f873a045330]
[fv-az1344-582:65568] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f873a09eb2c]
[fv-az1344-582:65568] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f873a04527e]
[fv-az1344-582:65568] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f873a0288ff]
[fv-az1344-582:65568] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f873a4a5ff5]
[fv-az1344-582:65568] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f873a4bb0da]
[fv-az1344-582:65568] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f873a4a5a55]
[fv-az1344-582:65568] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f873a4a5a6f]
[fv-az1344-582:65568] [ 8] plumed(+0x146dd)[0x55ce086646dd]
[fv-az1344-582:65568] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f873a02a1ca]
[fv-az1344-582:65568] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f873a02a28b]
[fv-az1344-582:65568] [11] plumed(+0x15365)[0x55ce08665365]
[fv-az1344-582:65568] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1344-582:65569] *** Process received signal ***
[fv-az1344-582:65569] Signal: Aborted (6)
[fv-az1344-582:65569] Signal code:  (-6)
[fv-az1344-582:65569] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f616a245330]
[fv-az1344-582:65569] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f616a29eb2c]
[fv-az1344-582:65569] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f616a24527e]
[fv-az1344-582:65569] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f616a2288ff]
[fv-az1344-582:65569] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f616a6a5ff5]
[fv-az1344-582:65569] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f616a6bb0da]
[fv-az1344-582:65569] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f616a6a5a55]
[fv-az1344-582:65569] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f616a6a5a6f]
[fv-az1344-582:65569] [ 8] plumed(+0x146dd)[0x55918b0026dd]
[fv-az1344-582:65569] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f616a22a1ca]
[fv-az1344-582:65569] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f616a22a28b]
[fv-az1344-582:65569] [11] plumed(+0x15365)[0x55918b003365]
[fv-az1344-582:65569] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1344-582 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
