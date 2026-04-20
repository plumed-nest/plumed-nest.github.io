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
[runnervmeorf1:08317] *** Process received signal ***
[runnervmeorf1:08317] Signal: Aborted (6)
[runnervmeorf1:08317] Signal code:  (-6)
[runnervmeorf1:08317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6e27a45330]
[runnervmeorf1:08317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6e27a9eb2c]
[runnervmeorf1:08317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6e27a4527e]
[runnervmeorf1:08317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6e27a288ff]
[runnervmeorf1:08317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6e27ea5ff5]
[runnervmeorf1:08317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6e27ebb0da]
[runnervmeorf1:08317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6e27ea5a55]
[runnervmeorf1:08317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6e27ea5a6f]
[runnervmeorf1:08317] [ 8] plumed_master(+0x146dd)[0x5616c1d216dd]
[runnervmeorf1:08317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6e27a2a1ca]
[runnervmeorf1:08317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6e27a2a28b]
[runnervmeorf1:08317] [11] plumed_master(+0x15365)[0x5616c1d22365]
[runnervmeorf1:08317] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmeorf1:08316] *** Process received signal ***
[runnervmeorf1:08316] Signal: Aborted (6)
[runnervmeorf1:08316] Signal code:  (-6)
[runnervmeorf1:08316] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6056445330]
[runnervmeorf1:08316] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f605649eb2c]
[runnervmeorf1:08316] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f605644527e]
[runnervmeorf1:08316] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f60564288ff]
[runnervmeorf1:08316] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60568a5ff5]
[runnervmeorf1:08316] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60568bb0da]
[runnervmeorf1:08316] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60568a5a55]
[runnervmeorf1:08316] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60568a5a6f]
[runnervmeorf1:08316] [ 8] plumed_master(+0x146dd)[0x55fd829726dd]
[runnervmeorf1:08316] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f605642a1ca]
[runnervmeorf1:08316] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f605642a28b]
[runnervmeorf1:08316] [11] plumed_master(+0x15365)[0x55fd82973365]
[runnervmeorf1:08316] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmeorf1 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
