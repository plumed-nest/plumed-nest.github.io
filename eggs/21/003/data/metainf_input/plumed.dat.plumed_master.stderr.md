**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az787-589:65618] *** Process received signal ***
[fv-az787-589:65618] Signal: Aborted (6)
[fv-az787-589:65618] Signal code:  (-6)
[fv-az787-589:65618] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbfd8245330]
[fv-az787-589:65618] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbfd829eb2c]
[fv-az787-589:65618] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbfd824527e]
[fv-az787-589:65618] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbfd82288ff]
[fv-az787-589:65618] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbfd86a5ff5]
[fv-az787-589:65618] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbfd86bb0da]
[fv-az787-589:65618] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbfd86a5a55]
[fv-az787-589:65618] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbfd86a5a6f]
[fv-az787-589:65618] [ 8] plumed_master(+0x146dd)[0x557b0eaa06dd]
[fv-az787-589:65618] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbfd822a1ca]
[fv-az787-589:65618] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbfd822a28b]
[fv-az787-589:65618] [11] plumed_master(+0x15365)[0x557b0eaa1365]
[fv-az787-589:65618] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az787-589:65617] *** Process received signal ***
[fv-az787-589:65617] Signal: Aborted (6)
[fv-az787-589:65617] Signal code:  (-6)
[fv-az787-589:65617] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1217c45330]
[fv-az787-589:65617] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1217c9eb2c]
[fv-az787-589:65617] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1217c4527e]
[fv-az787-589:65617] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1217c288ff]
[fv-az787-589:65617] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12180a5ff5]
[fv-az787-589:65617] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12180bb0da]
[fv-az787-589:65617] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12180a5a55]
[fv-az787-589:65617] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12180a5a6f]
[fv-az787-589:65617] [ 8] plumed_master(+0x146dd)[0x5619c347f6dd]
[fv-az787-589:65617] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1217c2a1ca]
[fv-az787-589:65617] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1217c2a28b]
[fv-az787-589:65617] [11] plumed_master(+0x15365)[0x5619c3480365]
[fv-az787-589:65617] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az787-589 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
