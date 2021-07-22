**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
../../code/Contacts.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../../code/Contacts.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
   93 |   for(unsigned int i=0; i<num_atomsa; i++)
      |                         ~^~~~~~~~~~~
../../code/Contacts.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
   99 |   for(unsigned int i=0; i<num_atomsb; i++)
      |                         ~^~~~~~~~~~~
../../code/Contacts.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
  124 |   for(unsigned int i=0;i<num_atomsa;++i){
      |                        ~^~~~~~~~~~~
../../code/Contacts.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
  129 |   for(unsigned int i=0;i<num_atomsb;++i){
      |                        ~^~~~~~~~~~~
../../code/PytorchModel.cpp:22:10: fatal error: Function.h: No such file or directory
   22 | #include "Function.h"
      |          ^~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:972, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh ../../code/PytorchModel.cpp

[fv-az95-172:31661] *** Process received signal ***
[fv-az95-172:31661] Signal: Aborted (6)
[fv-az95-172:31661] Signal code:  (-6)
[fv-az95-172:31661] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f025e06b210]
[fv-az95-172:31661] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f025e06b18b]
[fv-az95-172:31661] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f025e04a859]
[fv-az95-172:31661] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f025e2d2911]
[fv-az95-172:31661] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f025e2de38c]
[fv-az95-172:31661] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f025e2de3f7]
[fv-az95-172:31661] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f025e2de6fd]
[fv-az95-172:31661] [ 7] plumed_master(+0xf5b5)[0x55da4e2f95b5]
[fv-az95-172:31661] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f025e04c0b3]
[fv-az95-172:31661] [ 9] plumed_master(+0xf8be)[0x55da4e2f98be]
[fv-az95-172:31661] *** End of error message ***
</pre>
{% endraw %}
