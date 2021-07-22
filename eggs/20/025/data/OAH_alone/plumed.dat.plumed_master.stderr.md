**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAH_alone/plumed.dat   
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

[fv-az95-172:50832] *** Process received signal ***
[fv-az95-172:50832] Signal: Aborted (6)
[fv-az95-172:50832] Signal code:  (-6)
[fv-az95-172:50832] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8bc0701210]
[fv-az95-172:50832] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f8bc070118b]
[fv-az95-172:50832] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8bc06e0859]
[fv-az95-172:50832] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f8bc0968911]
[fv-az95-172:50832] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f8bc097438c]
[fv-az95-172:50832] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f8bc09743f7]
[fv-az95-172:50832] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f8bc09746fd]
[fv-az95-172:50832] [ 7] plumed_master(+0xf5b5)[0x55da16e565b5]
[fv-az95-172:50832] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f8bc06e20b3]
[fv-az95-172:50832] [ 9] plumed_master(+0xf8be)[0x55da16e568be]
[fv-az95-172:50832] *** End of error message ***
</pre>
{% endraw %}
