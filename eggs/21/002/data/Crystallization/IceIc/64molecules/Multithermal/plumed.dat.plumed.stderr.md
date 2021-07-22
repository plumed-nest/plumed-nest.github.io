**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIc/64molecules/Multithermal/plumed.dat   
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
[fv-az95-172:46974] *** Process received signal ***
[fv-az95-172:46974] Signal: Aborted (6)
[fv-az95-172:46974] Signal code:  (-6)
[fv-az95-172:46974] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ffb17c52210]
[fv-az95-172:46974] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ffb17c5218b]
[fv-az95-172:46974] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ffb17c31859]
[fv-az95-172:46974] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ffb17eb9911]
[fv-az95-172:46974] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ffb17ec538c]
[fv-az95-172:46974] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ffb17ec53f7]
[fv-az95-172:46974] [ 6] terminate called after throwing an instance of '/lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ffb17ec56a9]
[fv-az95-172:46974] [ 7] plumed(+0xf47d)[0x5570c7b8747d]
[fv-az95-172:46974] [ 8] plumed(+0x14004)[0x5570c7b8c004]
[fv-az95-172:46974] [ 9] plumed(+0xf698)[0x5570c7b87698]
[fv-az95-172:46974] [10] PLMD::Plumed::ExceptionError/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ffb17c330b3]
[fv-az95-172:46974] [11] plumed(+0xf76e)[0x5570c7b8776e]
[fv-az95-172:46974] *** End of error message ***
'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:46975] *** Process received signal ***
[fv-az95-172:46975] Signal: Aborted (6)
[fv-az95-172:46975] Signal code:  (-6)
[fv-az95-172:46975] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fce5ce22210]
[fv-az95-172:46975] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fce5ce2218b]
[fv-az95-172:46975] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fce5ce01859]
[fv-az95-172:46975] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fce5d089911]
[fv-az95-172:46975] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fce5d09538c]
[fv-az95-172:46975] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fce5d0953f7]
[fv-az95-172:46975] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fce5d0956a9]
[fv-az95-172:46975] [ 7] plumed(+0xf47d)[0x55fa47c5d47d]
[fv-az95-172:46975] [ 8] plumed(+0x14004)[0x55fa47c62004]
[fv-az95-172:46975] [ 9] plumed(+0xf698)[0x55fa47c5d698]
[fv-az95-172:46975] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fce5ce030b3]
[fv-az95-172:46975] [11] plumed(+0xf76e)[0x55fa47c5d76e]
[fv-az95-172:46975] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
