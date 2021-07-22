**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIc/96molecules/Multithermal/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47066] *** Process received signal ***
[fv-az95-172:47066] Signal: Aborted (6)
[fv-az95-172:47066] Signal code:  (-6)
[fv-az95-172:47066] [ 0] terminate called after throwing an instance of '/lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0a293a4210]
[fv-az95-172:47066] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0a293a418b]
[fv-az95-172:47066] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0a29383859]
[fv-az95-172:47066] [ 3] PLMD::Plumed::ExceptionError'
/lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0a2960b911]
[fv-az95-172:47066] [ 4]   what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
/lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0a2961738c]
[fv-az95-172:47066] [ 5] [fv-az95-172:47065] *** Process received signal ***
/lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0a296173f7]
[fv-az95-172:47066] [ 6] [fv-az95-172:47065] Signal: Aborted (6)
[fv-az95-172:47065] Signal code:  (-6)
/lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0a296176a9]
[fv-az95-172:47066] [ 7] plumed(+0xf47d)[0x55ed3282847d]
[fv-az95-172:47066] [ 8] plumed(+0x14004)[0x55ed3282d004]
[fv-az95-172:47066] [ 9] plumed(+0xf698)[0x55ed32828698]
[fv-az95-172:47066] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0a293850b3]
[fv-az95-172:47066] [11] plumed(+0xf76e)[0x55ed3282876e]
[fv-az95-172:47066] *** End of error message ***
[fv-az95-172:47065] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fcd11a6a210]
[fv-az95-172:47065] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fcd11a6a18b]
[fv-az95-172:47065] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fcd11a49859]
[fv-az95-172:47065] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fcd11cd1911]
[fv-az95-172:47065] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fcd11cdd38c]
[fv-az95-172:47065] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fcd11cdd3f7]
[fv-az95-172:47065] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fcd11cdd6a9]
[fv-az95-172:47065] [ 7] plumed(+0xf47d)[0x5651679dc47d]
[fv-az95-172:47065] [ 8] plumed(+0x14004)[0x5651679e1004]
[fv-az95-172:47065] [ 9] plumed(+0xf698)[0x5651679dc698]
[fv-az95-172:47065] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fcd11a4b0b3]
[fv-az95-172:47065] [11] plumed(+0xf76e)[0x5651679dc76e]
[fv-az95-172:47065] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
