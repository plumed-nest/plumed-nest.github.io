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
[runnervmw9dnm:09415] *** Process received signal ***
[runnervmw9dnm:09415] Signal: Aborted (6)
[runnervmw9dnm:09415] Signal code:  (-6)
[runnervmw9dnm:09415] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48ad245330]
[runnervmw9dnm:09415] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48ad29eb2c]
[runnervmw9dnm:09415] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48ad24527e]
[runnervmw9dnm:09415] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48ad2288ff]
[runnervmw9dnm:09415] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48ad6a5ff5]
[runnervmw9dnm:09415] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48ad6bb0da]
[runnervmw9dnm:09415] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48ad6a5a55]
[runnervmw9dnm:09415] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48ad6a5a6f]
[runnervmw9dnm:09415] [ 8] plumed(+0x146dd)[0x55afde53f6dd]
[runnervmw9dnm:09415] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48ad22a1ca]
[runnervmw9dnm:09415] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48ad22a28b]
[runnervmw9dnm:09415] [11] plumed(+0x15365)[0x55afde540365]
[runnervmw9dnm:09415] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmw9dnm:09414] *** Process received signal ***
[runnervmw9dnm:09414] Signal: Aborted (6)
[runnervmw9dnm:09414] Signal code:  (-6)
[runnervmw9dnm:09414] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff9dfe45330]
[runnervmw9dnm:09414] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff9dfe9eb2c]
[runnervmw9dnm:09414] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff9dfe4527e]
[runnervmw9dnm:09414] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff9dfe288ff]
[runnervmw9dnm:09414] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff9e02a5ff5]
[runnervmw9dnm:09414] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff9e02bb0da]
[runnervmw9dnm:09414] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff9e02a5a55]
[runnervmw9dnm:09414] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff9e02a5a6f]
[runnervmw9dnm:09414] [ 8] plumed(+0x146dd)[0x55ca6888e6dd]
[runnervmw9dnm:09414] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff9dfe2a1ca]
[runnervmw9dnm:09414] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff9dfe2a28b]
[runnervmw9dnm:09414] [11] plumed(+0x15365)[0x55ca6888f365]
[runnervmw9dnm:09414] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmw9dnm exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
