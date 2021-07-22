**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAH_G6/plumed.dat   
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

[fv-az95-172:50796] *** Process received signal ***
[fv-az95-172:50796] Signal: Aborted (6)
[fv-az95-172:50796] Signal code:  (-6)
[fv-az95-172:50796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2d0f9c5210]
[fv-az95-172:50796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2d0f9c518b]
[fv-az95-172:50796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2d0f9a4859]
[fv-az95-172:50796] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2d0fc2c911]
[fv-az95-172:50796] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2d0fc3838c]
[fv-az95-172:50796] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2d0fc383f7]
[fv-az95-172:50796] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f2d0fc386fd]
[fv-az95-172:50796] [ 7] plumed_master(+0xf5b5)[0x55826facc5b5]
[fv-az95-172:50796] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2d0f9a60b3]
[fv-az95-172:50796] [ 9] plumed_master(+0xf8be)[0x55826facc8be]
[fv-az95-172:50796] *** End of error message ***
</pre>
{% endraw %}
