**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIh/128molecules/Template/plumed.dat   
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
[fv-az95-172:47455] *** Process received signal ***
[fv-az95-172:47455] Signal: Aborted (6)
[fv-az95-172:47455] Signal code:  (-6)
[fv-az95-172:47455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f12db17b210]
[fv-az95-172:47455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f12db17b18b]
[fv-az95-172:47455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f12db15a859]
[fv-az95-172:47455] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f12db3e2911]
[fv-az95-172:47455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f12db3ee38c]
[fv-az95-172:47455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f12db3ee3f7]
[fv-az95-172:47455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f12db3ee6a9]
[fv-az95-172:47455] [ 7] plumed(+0xf47d)[0x55d11ceb847d]
[fv-az95-172:47455] [ 8] plumed(+0x14004)[0x55d11cebd004]
[fv-az95-172:47455] [ 9] plumed(+0xf698)[0x55d11ceb8698]
[fv-az95-172:47455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f12db15c0b3]
[fv-az95-172:47455] [11] plumed(+0xf76e)[0x55d11ceb876e]
[fv-az95-172:47455] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47456] *** Process received signal ***
[fv-az95-172:47456] Signal: Aborted (6)
[fv-az95-172:47456] Signal code:  (-6)
[fv-az95-172:47456] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1194431210]
[fv-az95-172:47456] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f119443118b]
[fv-az95-172:47456] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1194410859]
[fv-az95-172:47456] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1194698911]
[fv-az95-172:47456] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f11946a438c]
[fv-az95-172:47456] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f11946a43f7]
[fv-az95-172:47456] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f11946a46a9]
[fv-az95-172:47456] [ 7] plumed(+0xf47d)[0x55d0de46347d]
[fv-az95-172:47456] [ 8] plumed(+0x14004)[0x55d0de468004]
[fv-az95-172:47456] [ 9] plumed(+0xf698)[0x55d0de463698]
[fv-az95-172:47456] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f11944120b3]
[fv-az95-172:47456] [11] plumed(+0xf76e)[0x55d0de46376e]
[fv-az95-172:47456] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
