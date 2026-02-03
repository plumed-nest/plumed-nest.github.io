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
[runnervmkj6or:08055] *** Process received signal ***
[runnervmkj6or:08055] Signal: Aborted (6)
[runnervmkj6or:08055] Signal code:  (-6)
[runnervmkj6or:08055] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe970845330]
[runnervmkj6or:08055] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe97089eb2c]
[runnervmkj6or:08055] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe97084527e]
[runnervmkj6or:08055] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9708288ff]
[runnervmkj6or:08055] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe970ca5ff5]
[runnervmkj6or:08055] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe970cbb0da]
[runnervmkj6or:08055] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe970ca5a55]
[runnervmkj6or:08055] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe970ca5a6f]
[runnervmkj6or:08055] [ 8] plumed(+0x146dd)[0x55f0230386dd]
[runnervmkj6or:08055] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe97082a1ca]
[runnervmkj6or:08055] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe97082a28b]
[runnervmkj6or:08055] [11] plumed(+0x15365)[0x55f023039365]
[runnervmkj6or:08055] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmkj6or:08054] *** Process received signal ***
[runnervmkj6or:08054] Signal: Aborted (6)
[runnervmkj6or:08054] Signal code:  (-6)
[runnervmkj6or:08054] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f944b645330]
[runnervmkj6or:08054] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f944b69eb2c]
[runnervmkj6or:08054] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f944b64527e]
[runnervmkj6or:08054] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f944b6288ff]
[runnervmkj6or:08054] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f944baa5ff5]
[runnervmkj6or:08054] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f944babb0da]
[runnervmkj6or:08054] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f944baa5a55]
[runnervmkj6or:08054] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f944baa5a6f]
[runnervmkj6or:08054] [ 8] plumed(+0x146dd)[0x55fe9b3c86dd]
[runnervmkj6or:08054] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f944b62a1ca]
[runnervmkj6or:08054] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f944b62a28b]
[runnervmkj6or:08054] [11] plumed(+0x15365)[0x55fe9b3c9365]
[runnervmkj6or:08054] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmkj6or exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
