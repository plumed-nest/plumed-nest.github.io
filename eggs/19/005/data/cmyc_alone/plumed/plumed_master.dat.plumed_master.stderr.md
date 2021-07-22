**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs/19/005/)  
Stderr for source:  cmyc_alone/plumed/plumed_master.dat   
(download [zipped raw stdout](plumed_master.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[fv-az95-172:72871] *** Process received signal ***
[fv-az95-172:72871] Signal: Aborted (6)
[fv-az95-172:72871] Signal code:  (-6)
[fv-az95-172:72871] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f751a5ac210]
[fv-az95-172:72871] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f751a5ac18b]
[fv-az95-172:72871] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f751a58b859]
[fv-az95-172:72871] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f751a813911]
[fv-az95-172:72871] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f751a81f38c]
[fv-az95-172:72871] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f751a81f3f7]
[fv-az95-172:72871] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f751a81f6fd]
[fv-az95-172:72871] [ 7] plumed_master(+0xf5b5)[0x564bf21065b5]
[fv-az95-172:72871] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f751a58d0b3]
[fv-az95-172:72871] [ 9] plumed_master(+0xf8be)[0x564bf21068be]
[fv-az95-172:72871] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[fv-az95-172:72870] *** Process received signal ***
[fv-az95-172:72870] Signal: Aborted (6)
[fv-az95-172:72870] Signal code:  (-6)
[fv-az95-172:72870] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0f6da8b210]
[fv-az95-172:72870] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0f6da8b18b]
[fv-az95-172:72870] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0f6da6a859]
[fv-az95-172:72870] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0f6dcf2911]
[fv-az95-172:72870] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0f6dcfe38c]
[fv-az95-172:72870] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0f6dcfe3f7]
[fv-az95-172:72870] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f0f6dcfe6fd]
[fv-az95-172:72870] [ 7] plumed_master(+0xf5b5)[0x55cedaa8e5b5]
[fv-az95-172:72870] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0f6da6c0b3]
[fv-az95-172:72870] [ 9] plumed_master(+0xf8be)[0x55cedaa8e8be]
[fv-az95-172:72870] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
