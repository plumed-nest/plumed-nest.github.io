**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
../../code/TorchModel2D.cpp:25:10: fatal error: torch/torch.h: No such file or directory
   25 | #include <torch/torch.h>
      |          ^~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed"/scripts/mklib.sh ../../code/TorchModel2D.cpp

[fv-az95-172:31696] *** Process received signal ***
[fv-az95-172:31696] Signal: Aborted (6)
[fv-az95-172:31696] Signal code:  (-6)
[fv-az95-172:31696] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f53e51a4210]
[fv-az95-172:31696] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f53e51a418b]
[fv-az95-172:31696] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f53e5183859]
[fv-az95-172:31696] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f53e540b911]
[fv-az95-172:31696] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f53e541738c]
[fv-az95-172:31696] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f53e54173f7]
[fv-az95-172:31696] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f53e54176a9]
[fv-az95-172:31696] [ 7] plumed(+0xf47d)[0x55598045a47d]
[fv-az95-172:31696] [ 8] plumed(+0x14004)[0x55598045f004]
[fv-az95-172:31696] [ 9] plumed(+0xf698)[0x55598045a698]
[fv-az95-172:31696] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f53e51850b3]
[fv-az95-172:31696] [11] plumed(+0xf76e)[0x55598045a76e]
[fv-az95-172:31696] *** End of error message ***
</pre>
{% endraw %}
