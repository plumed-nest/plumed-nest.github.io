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
[fv-az1360-658:10490] *** Process received signal ***
[fv-az1360-658:10490] Signal: Aborted (6)
[fv-az1360-658:10490] Signal code:  (-6)
[fv-az1360-658:10490] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb92845330]
[fv-az1360-658:10490] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb9289eb2c]
[fv-az1360-658:10490] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb9284527e]
[fv-az1360-658:10490] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb928288ff]
[fv-az1360-658:10490] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb92ca5ff5]
[fv-az1360-658:10490] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb92cbb0da]
[fv-az1360-658:10490] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb92ca5a55]
[fv-az1360-658:10490] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb92ca5a6f]
[fv-az1360-658:10490] [ 8] plumed(+0x146dd)[0x55b8fca196dd]
[fv-az1360-658:10490] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb9282a1ca]
[fv-az1360-658:10490] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb9282a28b]
[fv-az1360-658:10490] [11] plumed(+0x15365)[0x55b8fca1a365]
[fv-az1360-658:10490] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1360-658:10491] *** Process received signal ***
[fv-az1360-658:10491] Signal: Aborted (6)
[fv-az1360-658:10491] Signal code:  (-6)
[fv-az1360-658:10491] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2890245330]
[fv-az1360-658:10491] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f289029eb2c]
[fv-az1360-658:10491] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f289024527e]
[fv-az1360-658:10491] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f28902288ff]
[fv-az1360-658:10491] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f28906a5ff5]
[fv-az1360-658:10491] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f28906bb0da]
[fv-az1360-658:10491] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f28906a5a55]
[fv-az1360-658:10491] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f28906a5a6f]
[fv-az1360-658:10491] [ 8] plumed(+0x146dd)[0x555b5832e6dd]
[fv-az1360-658:10491] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f289022a1ca]
[fv-az1360-658:10491] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f289022a28b]
[fv-az1360-658:10491] [11] plumed(+0x15365)[0x555b5832f365]
[fv-az1360-658:10491] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1360-658 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
