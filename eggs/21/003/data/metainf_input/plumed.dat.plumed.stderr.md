**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmmklqx:10310] *** Process received signal ***
[runnervmmklqx:10310] Signal: Aborted (6)
[runnervmmklqx:10310] Signal code:  (-6)
[runnervmmklqx:10310] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ef1e45330]
[runnervmmklqx:10310] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ef1e9eb2c]
[runnervmmklqx:10310] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ef1e4527e]
[runnervmmklqx:10310] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ef1e288ff]
[runnervmmklqx:10310] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ef22a5ff5]
[runnervmmklqx:10310] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ef22bb0da]
[runnervmmklqx:10310] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ef22a5a55]
[runnervmmklqx:10310] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ef22a5a6f]
[runnervmmklqx:10310] [ 8] plumed(+0x146dd)[0x55aa1f6e16dd]
[runnervmmklqx:10310] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ef1e2a1ca]
[runnervmmklqx:10310] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ef1e2a28b]
[runnervmmklqx:10310] [11] plumed(+0x15365)[0x55aa1f6e2365]
[runnervmmklqx:10310] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmmklqx:10311] *** Process received signal ***
[runnervmmklqx:10311] Signal: Aborted (6)
[runnervmmklqx:10311] Signal code:  (-6)
[runnervmmklqx:10311] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f76b6645330]
[runnervmmklqx:10311] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f76b669eb2c]
[runnervmmklqx:10311] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f76b664527e]
[runnervmmklqx:10311] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76b66288ff]
[runnervmmklqx:10311] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76b6aa5ff5]
[runnervmmklqx:10311] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76b6abb0da]
[runnervmmklqx:10311] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76b6aa5a55]
[runnervmmklqx:10311] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76b6aa5a6f]
[runnervmmklqx:10311] [ 8] plumed(+0x146dd)[0x55a1383b76dd]
[runnervmmklqx:10311] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f76b662a1ca]
[runnervmmklqx:10311] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f76b662a28b]
[runnervmmklqx:10311] [11] plumed(+0x15365)[0x55a1383b8365]
[runnervmmklqx:10311] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node runnervmmklqx exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
