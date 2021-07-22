**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  alanine/deepTDA_enhanced_sampling/plumed.dat   
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

[fv-az95-172:31538] *** Process received signal ***
[fv-az95-172:31538] Signal: Aborted (6)
[fv-az95-172:31538] Signal code:  (-6)
[fv-az95-172:31538] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7faf246b6210]
[fv-az95-172:31538] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7faf246b618b]
[fv-az95-172:31538] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7faf24695859]
[fv-az95-172:31538] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7faf2491d911]
[fv-az95-172:31538] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7faf2492938c]
[fv-az95-172:31538] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7faf249293f7]
[fv-az95-172:31538] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7faf249296a9]
[fv-az95-172:31538] [ 7] plumed(+0xf47d)[0x5628fe1eb47d]
[fv-az95-172:31538] [ 8] plumed(+0x14004)[0x5628fe1f0004]
[fv-az95-172:31538] [ 9] plumed(+0xf698)[0x5628fe1eb698]
[fv-az95-172:31538] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7faf246970b3]
[fv-az95-172:31538] [11] plumed(+0xf76e)[0x5628fe1eb76e]
[fv-az95-172:31538] *** End of error message ***
</pre>
{% endraw %}
