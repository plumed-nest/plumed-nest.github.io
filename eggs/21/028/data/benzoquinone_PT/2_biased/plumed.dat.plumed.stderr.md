**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  benzoquinone_PT/2_biased/plumed.dat   
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

[fv-az95-172:31597] *** Process received signal ***
[fv-az95-172:31597] Signal: Aborted (6)
[fv-az95-172:31597] Signal code:  (-6)
[fv-az95-172:31597] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc152e55210]
[fv-az95-172:31597] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc152e5518b]
[fv-az95-172:31597] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc152e34859]
[fv-az95-172:31597] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc1530bc911]
[fv-az95-172:31597] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc1530c838c]
[fv-az95-172:31597] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc1530c83f7]
[fv-az95-172:31597] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc1530c86a9]
[fv-az95-172:31597] [ 7] plumed(+0xf47d)[0x55dda4f0047d]
[fv-az95-172:31597] [ 8] plumed(+0x14004)[0x55dda4f05004]
[fv-az95-172:31597] [ 9] plumed(+0xf698)[0x55dda4f00698]
[fv-az95-172:31597] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc152e360b3]
[fv-az95-172:31597] [11] plumed(+0xf76e)[0x55dda4f0076e]
[fv-az95-172:31597] *** End of error message ***
</pre>
{% endraw %}
