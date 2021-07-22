**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  OAMe_G2/deepDA_enhanced_sampling/plumed.dat   
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

[fv-az95-172:31383] *** Process received signal ***
[fv-az95-172:31383] Signal: Aborted (6)
[fv-az95-172:31383] Signal code:  (-6)
[fv-az95-172:31383] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2afc5a9210]
[fv-az95-172:31383] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2afc5a918b]
[fv-az95-172:31383] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2afc588859]
[fv-az95-172:31383] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2afc810911]
[fv-az95-172:31383] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2afc81c38c]
[fv-az95-172:31383] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2afc81c3f7]
[fv-az95-172:31383] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2afc81c6a9]
[fv-az95-172:31383] [ 7] plumed(+0xf47d)[0x55e3762ed47d]
[fv-az95-172:31383] [ 8] plumed(+0x14004)[0x55e3762f2004]
[fv-az95-172:31383] [ 9] plumed(+0xf698)[0x55e3762ed698]
[fv-az95-172:31383] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2afc58a0b3]
[fv-az95-172:31383] [11] plumed(+0xf76e)[0x55e3762ed76e]
[fv-az95-172:31383] *** End of error message ***
</pre>
{% endraw %}
