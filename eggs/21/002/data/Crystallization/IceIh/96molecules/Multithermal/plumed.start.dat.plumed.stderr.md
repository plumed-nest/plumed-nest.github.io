**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIh/96molecules/Multithermal/plumed.start.dat   
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
[fv-az95-172:47299] *** Process received signal ***
[fv-az95-172:47299] Signal: Aborted (6)
[fv-az95-172:47299] Signal code:  (-6)
[fv-az95-172:47299] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4f7071a210]
[fv-az95-172:47299] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4f7071a18b]
[fv-az95-172:47299] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4f706f9859]
[fv-az95-172:47299] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4f70981911]
[fv-az95-172:47299] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4f7098d38c]
[fv-az95-172:47299] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4f7098d3f7]
[fv-az95-172:47299] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4f7098d6a9]
[fv-az95-172:47299] [ 7] plumed(+0xf47d)[0x55c5e156f47d]
[fv-az95-172:47299] [ 8] plumed(+0x14004)[0x55c5e1574004]
[fv-az95-172:47299] [ 9] plumed(+0xf698)[0x55c5e156f698]
[fv-az95-172:47299] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4f706fb0b3]
[fv-az95-172:47299] [11] plumed(+0xf76e)[0x55c5e156f76e]
[fv-az95-172:47299] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47298] *** Process received signal ***
[fv-az95-172:47298] Signal: Aborted (6)
[fv-az95-172:47298] Signal code:  (-6)
[fv-az95-172:47298] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa7aa402210]
[fv-az95-172:47298] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa7aa40218b]
[fv-az95-172:47298] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa7aa3e1859]
[fv-az95-172:47298] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa7aa669911]
[fv-az95-172:47298] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa7aa67538c]
[fv-az95-172:47298] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa7aa6753f7]
[fv-az95-172:47298] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa7aa6756a9]
[fv-az95-172:47298] [ 7] plumed(+0xf47d)[0x55968217d47d]
[fv-az95-172:47298] [ 8] plumed(+0x14004)[0x559682182004]
[fv-az95-172:47298] [ 9] plumed(+0xf698)[0x55968217d698]
[fv-az95-172:47298] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa7aa3e30b3]
[fv-az95-172:47298] [11] plumed(+0xf76e)[0x55968217d76e]
[fv-az95-172:47298] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
