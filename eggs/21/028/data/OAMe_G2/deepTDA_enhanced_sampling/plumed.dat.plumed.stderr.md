**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  OAMe_G2/deepTDA_enhanced_sampling/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
../../code/PytorchModel.cpp:22:10: fatal error: Function.h: No such file or directory
   22 | #include "Function.h"
      |          ^~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed"/scripts/mklib.sh ../../code/PytorchModel.cpp

[fv-az95-172:31419] *** Process received signal ***
[fv-az95-172:31419] Signal: Aborted (6)
[fv-az95-172:31419] Signal code:  (-6)
[fv-az95-172:31419] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f410b497210]
[fv-az95-172:31419] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f410b49718b]
[fv-az95-172:31419] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f410b476859]
[fv-az95-172:31419] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f410b6fe911]
[fv-az95-172:31419] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f410b70a38c]
[fv-az95-172:31419] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f410b70a3f7]
[fv-az95-172:31419] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f410b70a6a9]
[fv-az95-172:31419] [ 7] plumed(+0xf47d)[0x5617552f947d]
[fv-az95-172:31419] [ 8] plumed(+0x14004)[0x5617552fe004]
[fv-az95-172:31419] [ 9] plumed(+0xf698)[0x5617552f9698]
[fv-az95-172:31419] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f410b4780b3]
[fv-az95-172:31419] [11] plumed(+0xf76e)[0x5617552f976e]
[fv-az95-172:31419] *** End of error message ***
</pre>
{% endraw %}
