**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIc/216molecules/Template/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
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
[fv-az95-172:47362] *** Process received signal ***
[fv-az95-172:47362] Signal: Aborted (6)
[fv-az95-172:47362] Signal code:  (-6)
[fv-az95-172:47362] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fdbde7d5210]
[fv-az95-172:47362] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fdbde7d518b]
[fv-az95-172:47362] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fdbde7b4859]
[fv-az95-172:47362] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fdbdea3c911]
[fv-az95-172:47362] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fdbdea4838c]
[fv-az95-172:47362] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fdbdea483f7]
[fv-az95-172:47362] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fdbdea486a9]
[fv-az95-172:47362] [ 7] plumed(+0xf47d)[0x564ba0d8e47d]
[fv-az95-172:47362] [ 8] plumed(+0x14004)[0x564ba0d93004]
[fv-az95-172:47362] [ 9] plumed(+0xf698)[0x564ba0d8e698]
[fv-az95-172:47362] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fdbde7b60b3]
[fv-az95-172:47362] [11] plumed(+0xf76e)[0x564ba0d8e76e]
[fv-az95-172:47362] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47361] *** Process received signal ***
[fv-az95-172:47361] Signal: Aborted (6)
[fv-az95-172:47361] Signal code:  (-6)
[fv-az95-172:47361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f03f81a4210]
[fv-az95-172:47361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f03f81a418b]
[fv-az95-172:47361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f03f8183859]
[fv-az95-172:47361] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f03f840b911]
[fv-az95-172:47361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f03f841738c]
[fv-az95-172:47361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f03f84173f7]
[fv-az95-172:47361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f03f84176a9]
[fv-az95-172:47361] [ 7] plumed(+0xf47d)[0x562fe962a47d]
[fv-az95-172:47361] [ 8] plumed(+0x14004)[0x562fe962f004]
[fv-az95-172:47361] [ 9] plumed(+0xf698)[0x562fe962a698]
[fv-az95-172:47361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f03f81850b3]
[fv-az95-172:47361] [11] plumed(+0xf76e)[0x562fe962a76e]
[fv-az95-172:47361] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 1 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
