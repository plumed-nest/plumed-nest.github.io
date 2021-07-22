**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIh/288molecules/Template/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
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
[fv-az95-172:47549] *** Process received signal ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
[fv-az95-172:47549] Signal: Aborted (6)
[fv-az95-172:47549] Signal code:  (-6)
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47548] *** Process received signal ***
[fv-az95-172:47548] Signal: Aborted (6)
[fv-az95-172:47548] Signal code:  (-6)
[fv-az95-172:47548] [ 0] [fv-az95-172:47549] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fec04543210]
[fv-az95-172:47548] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fec0454318b]
[fv-az95-172:47548] [ 2] [ 0] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fec04522859]
[fv-az95-172:47548] [ 3] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ffa7b1de210]
/lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fec047aa911]
[fv-az95-172:47548] [ 4] [fv-az95-172:47549] [ 1] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fec047b638c]
[fv-az95-172:47548] [ 5] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ffa7b1de18b]
/lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fec047b63f7]
[fv-az95-172:47548] [ 6] [fv-az95-172:47549] [ 2] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fec047b66a9]
[fv-az95-172:47548] [ 7] plumed(+0xf47d)[0x55abd9d9f47d]
[fv-az95-172:47548] [ 8] plumed(+0x14004)[0x55abd9da4004]
[fv-az95-172:47548] [ 9] plumed(+0xf698)[0x55abd9d9f698]
[fv-az95-172:47548] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fec045240b3]
[fv-az95-172:47548] [11] plumed(+0xf76e)[0x55abd9d9f76e]
[fv-az95-172:47548] *** End of error message ***
/lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ffa7b1bd859]
[fv-az95-172:47549] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ffa7b445911]
[fv-az95-172:47549] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ffa7b45138c]
[fv-az95-172:47549] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ffa7b4513f7]
[fv-az95-172:47549] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ffa7b4516a9]
[fv-az95-172:47549] [ 7] plumed(+0xf47d)[0x55a86a11547d]
[fv-az95-172:47549] [ 8] plumed(+0x14004)[0x55a86a11a004]
[fv-az95-172:47549] [ 9] plumed(+0xf698)[0x55a86a115698]
[fv-az95-172:47549] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ffa7b1bf0b3]
[fv-az95-172:47549] [11] plumed(+0xf76e)[0x55a86a11576e]
[fv-az95-172:47549] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
