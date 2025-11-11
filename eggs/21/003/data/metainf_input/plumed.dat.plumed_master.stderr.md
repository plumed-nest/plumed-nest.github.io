**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmw9dnm:09449] *** Process received signal ***
[runnervmw9dnm:09449] Signal: Aborted (6)
[runnervmw9dnm:09449] Signal code:  (-6)
[runnervmw9dnm:09449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2250845330]
[runnervmw9dnm:09449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f225089eb2c]
[runnervmw9dnm:09449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f225084527e]
[runnervmw9dnm:09449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22508288ff]
[runnervmw9dnm:09449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2250ca5ff5]
[runnervmw9dnm:09449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2250cbb0da]
[runnervmw9dnm:09449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2250ca5a55]
[runnervmw9dnm:09449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2250ca5a6f]
[runnervmw9dnm:09449] [ 8] plumed_master(+0x146dd)[0x563678c9d6dd]
[runnervmw9dnm:09449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f225082a1ca]
[runnervmw9dnm:09449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f225082a28b]
[runnervmw9dnm:09449] [11] plumed_master(+0x15365)[0x563678c9e365]
[runnervmw9dnm:09449] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmw9dnm:09448] *** Process received signal ***
[runnervmw9dnm:09448] Signal: Aborted (6)
[runnervmw9dnm:09448] Signal code:  (-6)
[runnervmw9dnm:09448] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b35645330]
[runnervmw9dnm:09448] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b3569eb2c]
[runnervmw9dnm:09448] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b3564527e]
[runnervmw9dnm:09448] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b356288ff]
[runnervmw9dnm:09448] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b35aa5ff5]
[runnervmw9dnm:09448] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b35abb0da]
[runnervmw9dnm:09448] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b35aa5a55]
[runnervmw9dnm:09448] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b35aa5a6f]
[runnervmw9dnm:09448] [ 8] plumed_master(+0x146dd)[0x5641618086dd]
[runnervmw9dnm:09448] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b3562a1ca]
[runnervmw9dnm:09448] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b3562a28b]
[runnervmw9dnm:09448] [11] plumed_master(+0x15365)[0x564161809365]
[runnervmw9dnm:09448] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmw9dnm exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
