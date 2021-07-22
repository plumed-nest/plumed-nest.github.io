**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAMe_G5/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
../code/PytorchModel.cpp:22:10: fatal error: Function.h: No such file or directory
   22 | #include "Function.h"
      |          ^~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed"/scripts/mklib.sh ../code/PytorchModel.cpp

[fv-az95-172:51003] *** Process received signal ***
[fv-az95-172:51003] Signal: Aborted (6)
[fv-az95-172:51003] Signal code:  (-6)
[fv-az95-172:51003] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0ff72eb210]
[fv-az95-172:51003] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0ff72eb18b]
[fv-az95-172:51003] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0ff72ca859]
[fv-az95-172:51003] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0ff7552911]
[fv-az95-172:51003] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0ff755e38c]
[fv-az95-172:51003] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0ff755e3f7]
[fv-az95-172:51003] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0ff755e6a9]
[fv-az95-172:51003] [ 7] plumed(+0xf47d)[0x5650e656f47d]
[fv-az95-172:51003] [ 8] plumed(+0x14004)[0x5650e6574004]
[fv-az95-172:51003] [ 9] plumed(+0xf698)[0x5650e656f698]
[fv-az95-172:51003] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0ff72cc0b3]
[fv-az95-172:51003] [11] plumed(+0xf76e)[0x5650e656f76e]
[fv-az95-172:51003] *** End of error message ***
</pre>
{% endraw %}
