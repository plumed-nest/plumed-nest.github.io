**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIh/288molecules/Template/plumed.dat   
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
[fv-az95-172:47519] *** Process received signal ***
[fv-az95-172:47519] Signal: Aborted (6)
[fv-az95-172:47519] Signal code:  (-6)
[fv-az95-172:47519] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4fa5421210]
[fv-az95-172:47519] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4fa542118b]
[fv-az95-172:47519] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4fa5400859]
[fv-az95-172:47519] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4fa5688911]
[fv-az95-172:47519] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4fa569438c]
[fv-az95-172:47519] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4fa56943f7]
[fv-az95-172:47519] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4fa56946a9]
[fv-az95-172:47519] [ 7] plumed(+0xf47d)[0x55bd5c44247d]
[fv-az95-172:47519] [ 8] plumed(+0x14004)[0x55bd5c447004]
[fv-az95-172:47519] [ 9] plumed(+0xf698)[0x55bd5c442698]
[fv-az95-172:47519] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4fa54020b3]
[fv-az95-172:47519] [11] plumed(+0xf76e)[0x55bd5c44276e]
[fv-az95-172:47519] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47518] *** Process received signal ***
[fv-az95-172:47518] Signal: Aborted (6)
[fv-az95-172:47518] Signal code:  (-6)
[fv-az95-172:47518] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fee8fe23210]
[fv-az95-172:47518] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fee8fe2318b]
[fv-az95-172:47518] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fee8fe02859]
[fv-az95-172:47518] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fee9008a911]
[fv-az95-172:47518] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fee9009638c]
[fv-az95-172:47518] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fee900963f7]
[fv-az95-172:47518] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fee900966a9]
[fv-az95-172:47518] [ 7] plumed(+0xf47d)[0x5584b84fb47d]
[fv-az95-172:47518] [ 8] plumed(+0x14004)[0x5584b8500004]
[fv-az95-172:47518] [ 9] plumed(+0xf698)[0x5584b84fb698]
[fv-az95-172:47518] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fee8fe040b3]
[fv-az95-172:47518] [11] plumed(+0xf76e)[0x5584b84fb76e]
[fv-az95-172:47518] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
