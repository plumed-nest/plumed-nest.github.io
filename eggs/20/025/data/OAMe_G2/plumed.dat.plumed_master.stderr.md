**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAMe_G2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
../code/PytorchModel.cpp:22:10: fatal error: Function.h: No such file or directory
   22 | #include "Function.h"
      |          ^~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:972, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh ../code/PytorchModel.cpp

[fv-az95-172:50907] *** Process received signal ***
[fv-az95-172:50907] Signal: Aborted (6)
[fv-az95-172:50907] Signal code:  (-6)
[fv-az95-172:50907] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc412ac2210]
[fv-az95-172:50907] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc412ac218b]
[fv-az95-172:50907] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc412aa1859]
[fv-az95-172:50907] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc412d29911]
[fv-az95-172:50907] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc412d3538c]
[fv-az95-172:50907] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc412d353f7]
[fv-az95-172:50907] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fc412d356fd]
[fv-az95-172:50907] [ 7] plumed_master(+0xf5b5)[0x55d12614a5b5]
[fv-az95-172:50907] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc412aa30b3]
[fv-az95-172:50907] [ 9] plumed_master(+0xf8be)[0x55d12614a8be]
[fv-az95-172:50907] *** End of error message ***
</pre>
{% endraw %}
