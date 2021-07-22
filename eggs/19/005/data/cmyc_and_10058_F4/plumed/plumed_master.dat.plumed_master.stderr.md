**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs/19/005/)  
Stderr for source:  cmyc_and_10058_F4/plumed/plumed_master.dat   
(download [zipped raw stdout](plumed_master.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[fv-az95-172:72903] *** Process received signal ***
[fv-az95-172:72903] Signal: Aborted (6)
[fv-az95-172:72903] Signal code:  (-6)
[fv-az95-172:72903] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f275c98d210]
[fv-az95-172:72903] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f275c98d18b]
[fv-az95-172:72903] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f275c96c859]
[fv-az95-172:72903] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f275cbf4911]
[fv-az95-172:72903] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f275cc0038c]
[fv-az95-172:72903] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f275cc003f7]
[fv-az95-172:72903] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f275cc006fd]
[fv-az95-172:72903] [ 7] plumed_master(+0xf5b5)[0x560be3b805b5]
[fv-az95-172:72903] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f275c96e0b3]
[fv-az95-172:72903] [ 9] plumed_master(+0xf8be)[0x560be3b808be]
[fv-az95-172:72903] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[fv-az95-172:72902] *** Process received signal ***
[fv-az95-172:72902] Signal: Aborted (6)
[fv-az95-172:72902] Signal code:  (-6)
[fv-az95-172:72902] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3b65f20210]
[fv-az95-172:72902] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3b65f2018b]
[fv-az95-172:72902] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3b65eff859]
[fv-az95-172:72902] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3b66187911]
[fv-az95-172:72902] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3b6619338c]
[fv-az95-172:72902] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3b661933f7]
[fv-az95-172:72902] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f3b661936fd]
[fv-az95-172:72902] [ 7] plumed_master(+0xf5b5)[0x56131b7205b5]
[fv-az95-172:72902] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3b65f010b3]
[fv-az95-172:72902] [ 9] plumed_master(+0xf8be)[0x56131b7208be]
[fv-az95-172:72902] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
