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
[pkrvmbietmlfzoi:66084] *** Process received signal ***
[pkrvmbietmlfzoi:66084] Signal: Aborted (6)
[pkrvmbietmlfzoi:66084] Signal code:  (-6)
[pkrvmbietmlfzoi:66084] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7164245330]
[pkrvmbietmlfzoi:66084] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f716429eb2c]
[pkrvmbietmlfzoi:66084] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f716424527e]
[pkrvmbietmlfzoi:66084] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71642288ff]
[pkrvmbietmlfzoi:66084] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71646a5ff5]
[pkrvmbietmlfzoi:66084] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71646bb0da]
[pkrvmbietmlfzoi:66084] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71646a5a55]
[pkrvmbietmlfzoi:66084] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71646a5a6f]
[pkrvmbietmlfzoi:66084] [ 8] plumed(+0x146dd)[0x564bc1d596dd]
[pkrvmbietmlfzoi:66084] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f716422a1ca]
[pkrvmbietmlfzoi:66084] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f716422a28b]
[pkrvmbietmlfzoi:66084] [11] plumed(+0x15365)[0x564bc1d5a365]
[pkrvmbietmlfzoi:66084] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmbietmlfzoi:66085] *** Process received signal ***
[pkrvmbietmlfzoi:66085] Signal: Aborted (6)
[pkrvmbietmlfzoi:66085] Signal code:  (-6)
[pkrvmbietmlfzoi:66085] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f042fa45330]
[pkrvmbietmlfzoi:66085] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f042fa9eb2c]
[pkrvmbietmlfzoi:66085] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f042fa4527e]
[pkrvmbietmlfzoi:66085] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f042fa288ff]
[pkrvmbietmlfzoi:66085] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f042fea5ff5]
[pkrvmbietmlfzoi:66085] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f042febb0da]
[pkrvmbietmlfzoi:66085] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f042fea5a55]
[pkrvmbietmlfzoi:66085] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f042fea5a6f]
[pkrvmbietmlfzoi:66085] [ 8] plumed(+0x146dd)[0x55e12b5ab6dd]
[pkrvmbietmlfzoi:66085] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f042fa2a1ca]
[pkrvmbietmlfzoi:66085] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f042fa2a28b]
[pkrvmbietmlfzoi:66085] [11] plumed(+0x15365)[0x55e12b5ac365]
[pkrvmbietmlfzoi:66085] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmbietmlfzoi exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
