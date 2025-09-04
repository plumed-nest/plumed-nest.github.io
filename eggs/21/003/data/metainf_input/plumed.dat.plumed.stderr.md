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
[pkrvm7jw40e0xgp:10730] *** Process received signal ***
[pkrvm7jw40e0xgp:10730] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10730] Signal code:  (-6)
[pkrvm7jw40e0xgp:10730] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff6bbe45330]
[pkrvm7jw40e0xgp:10730] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff6bbe9eb2c]
[pkrvm7jw40e0xgp:10730] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff6bbe4527e]
[pkrvm7jw40e0xgp:10730] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6bbe288ff]
[pkrvm7jw40e0xgp:10730] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff6bc2a5ff5]
[pkrvm7jw40e0xgp:10730] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff6bc2bb0da]
[pkrvm7jw40e0xgp:10730] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff6bc2a5a55]
[pkrvm7jw40e0xgp:10730] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff6bc2a5a6f]
[pkrvm7jw40e0xgp:10730] [ 8] plumed(+0x146dd)[0x5647188506dd]
[pkrvm7jw40e0xgp:10730] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff6bbe2a1ca]
[pkrvm7jw40e0xgp:10730] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff6bbe2a28b]
[pkrvm7jw40e0xgp:10730] [11] plumed(+0x15365)[0x564718851365]
[pkrvm7jw40e0xgp:10730] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvm7jw40e0xgp:10729] *** Process received signal ***
[pkrvm7jw40e0xgp:10729] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10729] Signal code:  (-6)
[pkrvm7jw40e0xgp:10729] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc314a45330]
[pkrvm7jw40e0xgp:10729] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc314a9eb2c]
[pkrvm7jw40e0xgp:10729] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc314a4527e]
[pkrvm7jw40e0xgp:10729] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc314a288ff]
[pkrvm7jw40e0xgp:10729] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc314ea5ff5]
[pkrvm7jw40e0xgp:10729] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc314ebb0da]
[pkrvm7jw40e0xgp:10729] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc314ea5a55]
[pkrvm7jw40e0xgp:10729] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc314ea5a6f]
[pkrvm7jw40e0xgp:10729] [ 8] plumed(+0x146dd)[0x55f3971226dd]
[pkrvm7jw40e0xgp:10729] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc314a2a1ca]
[pkrvm7jw40e0xgp:10729] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc314a2a28b]
[pkrvm7jw40e0xgp:10729] [11] plumed(+0x15365)[0x55f397123365]
[pkrvm7jw40e0xgp:10729] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node pkrvm7jw40e0xgp exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
