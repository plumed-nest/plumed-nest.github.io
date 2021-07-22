**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
../../code/TorchModel2D.cpp:25:10: fatal error: torch/torch.h: No such file or directory
   25 | #include <torch/torch.h>
      |          ^~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:972, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh ../../code/TorchModel2D.cpp

[fv-az95-172:31721] *** Process received signal ***
[fv-az95-172:31721] Signal: Aborted (6)
[fv-az95-172:31721] Signal code:  (-6)
[fv-az95-172:31721] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f07510b1210]
[fv-az95-172:31721] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f07510b118b]
[fv-az95-172:31721] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0751090859]
[fv-az95-172:31721] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0751318911]
[fv-az95-172:31721] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f075132438c]
[fv-az95-172:31721] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f07513243f7]
[fv-az95-172:31721] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f07513246fd]
[fv-az95-172:31721] [ 7] plumed_master(+0xf5b5)[0x56458437c5b5]
[fv-az95-172:31721] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f07510920b3]
[fv-az95-172:31721] [ 9] plumed_master(+0xf8be)[0x56458437c8be]
[fv-az95-172:31721] *** End of error message ***
</pre>
{% endraw %}
