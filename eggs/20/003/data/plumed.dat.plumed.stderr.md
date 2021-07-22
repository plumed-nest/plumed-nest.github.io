**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
TD_TS-target-plumed2.6.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
   23 | #include "TargetDistribution.h"
      |          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed"/scripts/mklib.sh TD_TS-target-plumed2.6.cpp

[fv-az95-172:53673] *** Process received signal ***
[fv-az95-172:53673] Signal: Aborted (6)
[fv-az95-172:53673] Signal code:  (-6)
[fv-az95-172:53673] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9f2d09b210]
[fv-az95-172:53673] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9f2d09b18b]
[fv-az95-172:53673] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9f2d07a859]
[fv-az95-172:53673] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9f2d302911]
[fv-az95-172:53673] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9f2d30e38c]
[fv-az95-172:53673] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9f2d30e3f7]
[fv-az95-172:53673] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9f2d30e6a9]
[fv-az95-172:53673] [ 7] plumed(+0xf47d)[0x55a3897ee47d]
[fv-az95-172:53673] [ 8] plumed(+0x14004)[0x55a3897f3004]
[fv-az95-172:53673] [ 9] plumed(+0xf698)[0x55a3897ee698]
[fv-az95-172:53673] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9f2d07c0b3]
[fv-az95-172:53673] [11] plumed(+0xf76e)[0x55a3897ee76e]
[fv-az95-172:53673] *** End of error message ***
</pre>
{% endraw %}
