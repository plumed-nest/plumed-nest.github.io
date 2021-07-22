**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIh/96molecules/Multithermal/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
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
[fv-az95-172:47267] *** Process received signal ***
[fv-az95-172:47267] Signal: Aborted (6)
[fv-az95-172:47267] Signal code:  (-6)
[fv-az95-172:47267] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f102c1c2210]
[fv-az95-172:47267] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f102c1c218b]
[fv-az95-172:47267] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f102c1a1859]
[fv-az95-172:47267] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f102c429911]
[fv-az95-172:47267] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f102c43538c]
[fv-az95-172:47267] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f102c4353f7]
[fv-az95-172:47267] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f102c4356a9]
[fv-az95-172:47267] [ 7] plumed(+0xf47d)[0x5561f3a7b47d]
[fv-az95-172:47267] [ 8] plumed(+0x14004)[0x5561f3a80004]
[fv-az95-172:47267] [ 9] plumed(+0xf698)[0x5561f3a7b698]
[fv-az95-172:47267] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f102c1a30b3]
[fv-az95-172:47267] [11] plumed(+0xf76e)[0x5561f3a7b76e]
[fv-az95-172:47267] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47268] *** Process received signal ***
[fv-az95-172:47268] Signal: Aborted (6)
[fv-az95-172:47268] Signal code:  (-6)
[fv-az95-172:47268] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f014e25e210]
[fv-az95-172:47268] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f014e25e18b]
[fv-az95-172:47268] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f014e23d859]
[fv-az95-172:47268] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f014e4c5911]
[fv-az95-172:47268] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f014e4d138c]
[fv-az95-172:47268] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f014e4d13f7]
[fv-az95-172:47268] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f014e4d16a9]
[fv-az95-172:47268] [ 7] plumed(+0xf47d)[0x55a5a831347d]
[fv-az95-172:47268] [ 8] plumed(+0x14004)[0x55a5a8318004]
[fv-az95-172:47268] [ 9] plumed(+0xf698)[0x55a5a8313698]
[fv-az95-172:47268] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f014e23f0b3]
[fv-az95-172:47268] [11] plumed(+0xf76e)[0x55a5a831376e]
[fv-az95-172:47268] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
