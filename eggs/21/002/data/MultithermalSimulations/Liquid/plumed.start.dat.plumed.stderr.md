**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/Liquid/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=350 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47611] *** Process received signal ***
[fv-az95-172:47611] Signal: Aborted (6)
[fv-az95-172:47611] Signal code:  (-6)
[fv-az95-172:47611] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9d165cb210]
[fv-az95-172:47611] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9d165cb18b]
[fv-az95-172:47611] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9d165aa859]
[fv-az95-172:47611] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9d16832911]
[fv-az95-172:47611] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9d1683e38c]
[fv-az95-172:47611] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9d1683e3f7]
[fv-az95-172:47611] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9d1683e6a9]
[fv-az95-172:47611] [ 7] plumed(+0xf47d)[0x559f7885c47d]
[fv-az95-172:47611] [ 8] plumed(+0x14004)[0x559f78861004]
[fv-az95-172:47611] [ 9] plumed(+0xf698)[0x559f7885c698]
[fv-az95-172:47611] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9d165ac0b3]
[fv-az95-172:47611] [11] plumed(+0xf76e)[0x559f7885c76e]
[fv-az95-172:47611] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=350 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47610] *** Process received signal ***
[fv-az95-172:47610] Signal: Aborted (6)
[fv-az95-172:47610] Signal code:  (-6)
[fv-az95-172:47610] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f35ace6f210]
[fv-az95-172:47610] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f35ace6f18b]
[fv-az95-172:47610] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f35ace4e859]
[fv-az95-172:47610] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f35ad0d6911]
[fv-az95-172:47610] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f35ad0e238c]
[fv-az95-172:47610] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f35ad0e23f7]
[fv-az95-172:47610] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f35ad0e26a9]
[fv-az95-172:47610] [ 7] plumed(+0xf47d)[0x5572d763747d]
[fv-az95-172:47610] [ 8] plumed(+0x14004)[0x5572d763c004]
[fv-az95-172:47610] [ 9] plumed(+0xf698)[0x5572d7637698]
[fv-az95-172:47610] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f35ace500b3]
[fv-az95-172:47610] [11] plumed(+0xf76e)[0x5572d763776e]
[fv-az95-172:47610] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
