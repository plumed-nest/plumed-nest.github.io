**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIc/64molecules/Template/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
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
[fv-az95-172:47393] *** Process received signal ***
[fv-az95-172:47393] Signal: Aborted (6)
[fv-az95-172:47393] Signal code:  (-6)
[fv-az95-172:47393] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5e4cf3d210]
[fv-az95-172:47393] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5e4cf3d18b]
[fv-az95-172:47393] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5e4cf1c859]
[fv-az95-172:47393] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5e4d1a4911]
[fv-az95-172:47393] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f5e4d1b038c]
[fv-az95-172:47393] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f5e4d1b03f7]
[fv-az95-172:47393] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f5e4d1b06a9]
[fv-az95-172:47393] [ 7] plumed(+0xf47d)[0x5593724bf47d]
[fv-az95-172:47393] [ 8] plumed(+0x14004)[0x5593724c4004]
[fv-az95-172:47393] [ 9] plumed(+0xf698)[0x5593724bf698]
[fv-az95-172:47393] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5e4cf1e0b3]
[fv-az95-172:47393] [11] plumed(+0xf76e)[0x5593724bf76e]
[fv-az95-172:47393] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47394] *** Process received signal ***
[fv-az95-172:47394] Signal: Aborted (6)
[fv-az95-172:47394] Signal code:  (-6)
[fv-az95-172:47394] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f648cefd210]
[fv-az95-172:47394] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f648cefd18b]
[fv-az95-172:47394] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f648cedc859]
[fv-az95-172:47394] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f648d164911]
[fv-az95-172:47394] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f648d17038c]
[fv-az95-172:47394] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f648d1703f7]
[fv-az95-172:47394] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f648d1706a9]
[fv-az95-172:47394] [ 7] plumed(+0xf47d)[0x5620bfabb47d]
[fv-az95-172:47394] [ 8] plumed(+0x14004)[0x5620bfac0004]
[fv-az95-172:47394] [ 9] plumed(+0xf698)[0x5620bfabb698]
[fv-az95-172:47394] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f648cede0b3]
[fv-az95-172:47394] [11] plumed(+0xf76e)[0x5620bfabb76e]
[fv-az95-172:47394] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
