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
[runnervmeorf1:08282] *** Process received signal ***
[runnervmeorf1:08282] Signal: Aborted (6)
[runnervmeorf1:08282] Signal code:  (-6)
[runnervmeorf1:08282] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad58245330]
[runnervmeorf1:08282] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad5829eb2c]
[runnervmeorf1:08282] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad5824527e]
[runnervmeorf1:08282] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad582288ff]
[runnervmeorf1:08282] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad586a5ff5]
[runnervmeorf1:08282] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad586bb0da]
[runnervmeorf1:08282] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad586a5a55]
[runnervmeorf1:08282] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad586a5a6f]
[runnervmeorf1:08282] [ 8] plumed(+0x146dd)[0x55b0c1fcd6dd]
[runnervmeorf1:08282] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad5822a1ca]
[runnervmeorf1:08282] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad5822a28b]
[runnervmeorf1:08282] [11] plumed(+0x15365)[0x55b0c1fce365]
[runnervmeorf1:08282] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmeorf1:08281] *** Process received signal ***
[runnervmeorf1:08281] Signal: Aborted (6)
[runnervmeorf1:08281] Signal code:  (-6)
[runnervmeorf1:08281] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8c9ae45330]
[runnervmeorf1:08281] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8c9ae9eb2c]
[runnervmeorf1:08281] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8c9ae4527e]
[runnervmeorf1:08281] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8c9ae288ff]
[runnervmeorf1:08281] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8c9b2a5ff5]
[runnervmeorf1:08281] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8c9b2bb0da]
[runnervmeorf1:08281] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8c9b2a5a55]
[runnervmeorf1:08281] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8c9b2a5a6f]
[runnervmeorf1:08281] [ 8] plumed(+0x146dd)[0x5622fb6b26dd]
[runnervmeorf1:08281] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8c9ae2a1ca]
[runnervmeorf1:08281] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8c9ae2a28b]
[runnervmeorf1:08281] [11] plumed(+0x15365)[0x5622fb6b3365]
[runnervmeorf1:08281] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmeorf1 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
