**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIc/96molecules/Multithermal/plumed.dat   
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
[fv-az95-172:47036] *** Process received signal ***
[fv-az95-172:47036] Signal: Aborted (6)
[fv-az95-172:47036] Signal code:  (-6)
[fv-az95-172:47036] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3e8ebcd210]
[fv-az95-172:47036] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3e8ebcd18b]
[fv-az95-172:47036] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3e8ebac859]
[fv-az95-172:47036] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3e8ee34911]
[fv-az95-172:47036] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3e8ee4038c]
[fv-az95-172:47036] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3e8ee403f7]
[fv-az95-172:47036] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f3e8ee406a9]
[fv-az95-172:47036] [ 7] plumed(+0xf47d)[0x55e3cab7e47d]
[fv-az95-172:47036] [ 8] plumed(+0x14004)[0x55e3cab83004]
[fv-az95-172:47036] [ 9] plumed(+0xf698)[0x55e3cab7e698]
[fv-az95-172:47036] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3e8ebae0b3]
[fv-az95-172:47036] [11] plumed(+0xf76e)[0x55e3cab7e76e]
[fv-az95-172:47036] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47035] *** Process received signal ***
[fv-az95-172:47035] Signal: Aborted (6)
[fv-az95-172:47035] Signal code:  (-6)
[fv-az95-172:47035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fcc32580210]
[fv-az95-172:47035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fcc3258018b]
[fv-az95-172:47035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fcc3255f859]
[fv-az95-172:47035] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fcc327e7911]
[fv-az95-172:47035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fcc327f338c]
[fv-az95-172:47035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fcc327f33f7]
[fv-az95-172:47035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fcc327f36a9]
[fv-az95-172:47035] [ 7] plumed(+0xf47d)[0x55c8d7c4547d]
[fv-az95-172:47035] [ 8] plumed(+0x14004)[0x55c8d7c4a004]
[fv-az95-172:47035] [ 9] plumed(+0xf698)[0x55c8d7c45698]
[fv-az95-172:47035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fcc325610b3]
[fv-az95-172:47035] [11] plumed(+0xf76e)[0x55c8d7c4576e]
[fv-az95-172:47035] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
