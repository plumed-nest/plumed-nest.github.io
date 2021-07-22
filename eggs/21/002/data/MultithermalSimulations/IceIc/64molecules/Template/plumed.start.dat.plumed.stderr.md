**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIc/64molecules/Template/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47425] *** Process received signal ***
[fv-az95-172:47425] Signal: Aborted (6)
[fv-az95-172:47425] Signal code:  (-6)
[fv-az95-172:47425] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fd4543c3210]
[fv-az95-172:47425] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fd4543c318b]
[fv-az95-172:47425] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fd4543a2859]
[fv-az95-172:47425] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fd45462a911]
[fv-az95-172:47425] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fd45463638c]
[fv-az95-172:47425] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fd4546363f7]
[fv-az95-172:47425] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fd4546366a9]
[fv-az95-172:47425] [ 7] plumed(+0xf47d)[0x564cb94e547d]
[fv-az95-172:47425] [ 8] plumed(+0x14004)[0x564cb94ea004]
[fv-az95-172:47425] [ 9] plumed(+0xf698)[0x564cb94e5698]
[fv-az95-172:47425] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fd4543a40b3]
[fv-az95-172:47425] [11] plumed(+0xf76e)[0x564cb94e576e]
[fv-az95-172:47425] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47424] *** Process received signal ***
[fv-az95-172:47424] Signal: Aborted (6)
[fv-az95-172:47424] Signal code:  (-6)
[fv-az95-172:47424] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9c458f1210]
[fv-az95-172:47424] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9c458f118b]
[fv-az95-172:47424] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9c458d0859]
[fv-az95-172:47424] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9c45b58911]
[fv-az95-172:47424] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9c45b6438c]
[fv-az95-172:47424] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9c45b643f7]
[fv-az95-172:47424] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9c45b646a9]
[fv-az95-172:47424] [ 7] plumed(+0xf47d)[0x55746b3ea47d]
[fv-az95-172:47424] [ 8] plumed(+0x14004)[0x55746b3ef004]
[fv-az95-172:47424] [ 9] plumed(+0xf698)[0x55746b3ea698]
[fv-az95-172:47424] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9c458d20b3]
[fv-az95-172:47424] [11] plumed(+0xf76e)[0x55746b3ea76e]
[fv-az95-172:47424] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
