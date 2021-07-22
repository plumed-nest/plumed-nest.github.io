**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIc/216molecules/Template/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47329] *** Process received signal ***
[fv-az95-172:47329] Signal: Aborted (6)
[fv-az95-172:47329] Signal code:  (-6)
[fv-az95-172:47329] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5932360210]
[fv-az95-172:47329] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f593236018b]
[fv-az95-172:47329] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f593233f859]
[fv-az95-172:47329] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f59325c7911]
[fv-az95-172:47329] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f59325d338c]
[fv-az95-172:47329] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f59325d33f7]
[fv-az95-172:47329] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f59325d36a9]
[fv-az95-172:47329] [ 7] plumed(+0xf47d)[0x556cc263347d]
[fv-az95-172:47329] [ 8] plumed(+0x14004)[0x556cc2638004]
[fv-az95-172:47329] [ 9] plumed(+0xf698)[0x556cc2633698]
[fv-az95-172:47329] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f59323410b3]
[fv-az95-172:47329] [11] plumed(+0xf76e)[0x556cc263376e]
[fv-az95-172:47329] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47328] *** Process received signal ***
[fv-az95-172:47328] Signal: Aborted (6)
[fv-az95-172:47328] Signal code:  (-6)
[fv-az95-172:47328] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fcfb2c4c210]
[fv-az95-172:47328] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fcfb2c4c18b]
[fv-az95-172:47328] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fcfb2c2b859]
[fv-az95-172:47328] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fcfb2eb3911]
[fv-az95-172:47328] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fcfb2ebf38c]
[fv-az95-172:47328] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fcfb2ebf3f7]
[fv-az95-172:47328] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fcfb2ebf6a9]
[fv-az95-172:47328] [ 7] plumed(+0xf47d)[0x55d3b0a1947d]
[fv-az95-172:47328] [ 8] plumed(+0x14004)[0x55d3b0a1e004]
[fv-az95-172:47328] [ 9] plumed(+0xf698)[0x55d3b0a19698]
[fv-az95-172:47328] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fcfb2c2d0b3]
[fv-az95-172:47328] [11] plumed(+0xf76e)[0x55d3b0a1976e]
[fv-az95-172:47328] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
