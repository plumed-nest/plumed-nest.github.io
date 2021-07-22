**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIh/128molecules/Template/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
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
[fv-az95-172:47487] *** Process received signal ***
[fv-az95-172:47487] Signal: Aborted (6)
[fv-az95-172:47487] Signal code:  (-6)
[fv-az95-172:47487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f275431e210]
[fv-az95-172:47487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f275431e18b]
[fv-az95-172:47487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f27542fd859]
[fv-az95-172:47487] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2754585911]
[fv-az95-172:47487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f275459138c]
[fv-az95-172:47487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f27545913f7]
[fv-az95-172:47487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f27545916a9]
[fv-az95-172:47487] [ 7] plumed(+0xf47d)[0x564f271c147d]
[fv-az95-172:47487] [ 8] plumed(+0x14004)[0x564f271c6004]
[fv-az95-172:47487] [ 9] plumed(+0xf698)[0x564f271c1698]
[fv-az95-172:47487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f27542ff0b3]
[fv-az95-172:47487] [11] plumed(+0xf76e)[0x564f271c176e]
[fv-az95-172:47487] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47488] *** Process received signal ***
[fv-az95-172:47488] Signal: Aborted (6)
[fv-az95-172:47488] Signal code:  (-6)
[fv-az95-172:47488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2b1c800210]
[fv-az95-172:47488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2b1c80018b]
[fv-az95-172:47488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2b1c7df859]
[fv-az95-172:47488] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2b1ca67911]
[fv-az95-172:47488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2b1ca7338c]
[fv-az95-172:47488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2b1ca733f7]
[fv-az95-172:47488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2b1ca736a9]
[fv-az95-172:47488] [ 7] plumed(+0xf47d)[0x563da2c1847d]
[fv-az95-172:47488] [ 8] plumed(+0x14004)[0x563da2c1d004]
[fv-az95-172:47488] [ 9] plumed(+0xf698)[0x563da2c18698]
[fv-az95-172:47488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2b1c7e10b3]
[fv-az95-172:47488] [11] plumed(+0xf76e)[0x563da2c1876e]
[fv-az95-172:47488] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
