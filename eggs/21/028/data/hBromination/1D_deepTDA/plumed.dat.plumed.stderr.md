**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
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
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed"/scripts/mklib.sh ../../code/PytorchModel.cpp

[fv-az95-172:31633] *** Process received signal ***
[fv-az95-172:31633] Signal: Aborted (6)
[fv-az95-172:31633] Signal code:  (-6)
[fv-az95-172:31633] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc5d4454210]
[fv-az95-172:31633] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc5d445418b]
[fv-az95-172:31633] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc5d4433859]
[fv-az95-172:31633] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc5d46bb911]
[fv-az95-172:31633] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc5d46c738c]
[fv-az95-172:31633] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc5d46c73f7]
[fv-az95-172:31633] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc5d46c76a9]
[fv-az95-172:31633] [ 7] plumed(+0xf47d)[0x556544e0147d]
[fv-az95-172:31633] [ 8] plumed(+0x14004)[0x556544e06004]
[fv-az95-172:31633] [ 9] plumed(+0xf698)[0x556544e01698]
[fv-az95-172:31633] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc5d44350b3]
[fv-az95-172:31633] [11] plumed(+0xf76e)[0x556544e0176e]
[fv-az95-172:31633] *** End of error message ***
</pre>
{% endraw %}
