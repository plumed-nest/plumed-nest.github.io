**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
TD_TS-target-plumed2.6.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
   23 | #include "TargetDistribution.h"
      |          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:972, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh TD_TS-target-plumed2.6.cpp

[fv-az95-172:53687] *** Process received signal ***
[fv-az95-172:53687] Signal: Aborted (6)
[fv-az95-172:53687] Signal code:  (-6)
[fv-az95-172:53687] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f61d4097210]
[fv-az95-172:53687] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f61d409718b]
[fv-az95-172:53687] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f61d4076859]
[fv-az95-172:53687] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f61d42fe911]
[fv-az95-172:53687] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f61d430a38c]
[fv-az95-172:53687] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f61d430a3f7]
[fv-az95-172:53687] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f61d430a6fd]
[fv-az95-172:53687] [ 7] plumed_master(+0xf5b5)[0x56071ae0a5b5]
[fv-az95-172:53687] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f61d40780b3]
[fv-az95-172:53687] [ 9] plumed_master(+0xf8be)[0x56071ae0a8be]
[fv-az95-172:53687] *** End of error message ***
</pre>
{% endraw %}
