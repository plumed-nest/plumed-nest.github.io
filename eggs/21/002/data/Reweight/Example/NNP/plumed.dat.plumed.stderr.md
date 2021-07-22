**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Reweight/Example/NNP/plumed.dat   
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
[fv-az95-172:47642] *** Process received signal ***
[fv-az95-172:47642] Signal: Aborted (6)
[fv-az95-172:47642] Signal code:  (-6)
[fv-az95-172:47642] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fccc2868210]
[fv-az95-172:47642] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fccc286818b]
[fv-az95-172:47642] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fccc2847859]
[fv-az95-172:47642] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fccc2acf911]
[fv-az95-172:47642] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fccc2adb38c]
[fv-az95-172:47642] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fccc2adb3f7]
[fv-az95-172:47642] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fccc2adb6a9]
[fv-az95-172:47642] [ 7] plumed(+0xf47d)[0x561d3329a47d]
[fv-az95-172:47642] [ 8] plumed(+0x14004)[0x561d3329f004]
[fv-az95-172:47642] [ 9] plumed(+0xf698)[0x561d3329a698]
[fv-az95-172:47642] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fccc28490b3]
[fv-az95-172:47642] [11] plumed(+0xf76e)[0x561d3329a76e]
[fv-az95-172:47642] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47641] *** Process received signal ***
[fv-az95-172:47641] Signal: Aborted (6)
[fv-az95-172:47641] Signal code:  (-6)
[fv-az95-172:47641] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff945c3d210]
[fv-az95-172:47641] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff945c3d18b]
[fv-az95-172:47641] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff945c1c859]
[fv-az95-172:47641] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff945ea4911]
[fv-az95-172:47641] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff945eb038c]
[fv-az95-172:47641] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff945eb03f7]
[fv-az95-172:47641] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff945eb06a9]
[fv-az95-172:47641] [ 7] plumed(+0xf47d)[0x559d9b69947d]
[fv-az95-172:47641] [ 8] plumed(+0x14004)[0x559d9b69e004]
[fv-az95-172:47641] [ 9] plumed(+0xf698)[0x559d9b699698]
[fv-az95-172:47641] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff945c1e0b3]
[fv-az95-172:47641] [11] plumed(+0xf76e)[0x559d9b69976e]
[fv-az95-172:47641] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
