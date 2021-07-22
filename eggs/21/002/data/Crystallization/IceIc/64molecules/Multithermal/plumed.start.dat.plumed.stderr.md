**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIc/64molecules/Multithermal/plumed.start.dat   
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
[fv-az95-172:47005] *** Process received signal ***
[fv-az95-172:47005] Signal: Aborted (6)
[fv-az95-172:47005] Signal code:  (-6)
[fv-az95-172:47005] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4ea3b39210]
[fv-az95-172:47005] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4ea3b3918b]
[fv-az95-172:47005] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4ea3b18859]
[fv-az95-172:47005] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4ea3da0911]
[fv-az95-172:47005] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4ea3dac38c]
[fv-az95-172:47005] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4ea3dac3f7]
[fv-az95-172:47005] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4ea3dac6a9]
[fv-az95-172:47005] [ 7] plumed(+0xf47d)[0x55f8fd4e647d]
[fv-az95-172:47005] [ 8] plumed(+0x14004)[0x55f8fd4eb004]
[fv-az95-172:47005] [ 9] plumed(+0xf698)[0x55f8fd4e6698]
[fv-az95-172:47005] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4ea3b1a0b3]
[fv-az95-172:47005] [11] plumed(+0xf76e)[0x55f8fd4e676e]
[fv-az95-172:47005] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47006] *** Process received signal ***
[fv-az95-172:47006] Signal: Aborted (6)
[fv-az95-172:47006] Signal code:  (-6)
[fv-az95-172:47006] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7feede8d9210]
[fv-az95-172:47006] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7feede8d918b]
[fv-az95-172:47006] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7feede8b8859]
[fv-az95-172:47006] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7feedeb40911]
[fv-az95-172:47006] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7feedeb4c38c]
[fv-az95-172:47006] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7feedeb4c3f7]
[fv-az95-172:47006] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7feedeb4c6a9]
[fv-az95-172:47006] [ 7] plumed(+0xf47d)[0x564caa94447d]
[fv-az95-172:47006] [ 8] plumed(+0x14004)[0x564caa949004]
[fv-az95-172:47006] [ 9] plumed(+0xf698)[0x564caa944698]
[fv-az95-172:47006] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7feede8ba0b3]
[fv-az95-172:47006] [11] plumed(+0xf76e)[0x564caa94476e]
[fv-az95-172:47006] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
