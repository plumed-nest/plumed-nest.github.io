**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/Liquid/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
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
[fv-az95-172:47581] *** Process received signal ***
[fv-az95-172:47581] Signal: Aborted (6)
[fv-az95-172:47581] Signal code:  (-6)
[fv-az95-172:47581] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fae888ba210]
[fv-az95-172:47581] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fae888ba18b]
[fv-az95-172:47581] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fae88899859]
[fv-az95-172:47581] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fae88b21911]
[fv-az95-172:47581] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fae88b2d38c]
[fv-az95-172:47581] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fae88b2d3f7]
[fv-az95-172:47581] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fae88b2d6a9]
[fv-az95-172:47581] [ 7] plumed(+0xf47d)[0x55dde040447d]
[fv-az95-172:47581] [ 8] plumed(+0x14004)[0x55dde0409004]
[fv-az95-172:47581] [ 9] plumed(+0xf698)[0x55dde0404698]
[fv-az95-172:47581] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fae8889b0b3]
[fv-az95-172:47581] [11] plumed(+0xf76e)[0x55dde040476e]
[fv-az95-172:47581] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=350 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[fv-az95-172:47580] *** Process received signal ***
[fv-az95-172:47580] Signal: Aborted (6)
[fv-az95-172:47580] Signal code:  (-6)
[fv-az95-172:47580] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0bc546d210]
[fv-az95-172:47580] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0bc546d18b]
[fv-az95-172:47580] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0bc544c859]
[fv-az95-172:47580] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0bc56d4911]
[fv-az95-172:47580] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0bc56e038c]
[fv-az95-172:47580] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0bc56e03f7]
[fv-az95-172:47580] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0bc56e06a9]
[fv-az95-172:47580] [ 7] plumed(+0xf47d)[0x55de6f53547d]
[fv-az95-172:47580] [ 8] plumed(+0x14004)[0x55de6f53a004]
[fv-az95-172:47580] [ 9] plumed(+0xf698)[0x55de6f535698]
[fv-az95-172:47580] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0bc544e0b3]
[fv-az95-172:47580] [11] plumed(+0xf76e)[0x55de6f53576e]
[fv-az95-172:47580] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
