**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.xUaLMv.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.xUaLMv.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.xUaLMv.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.xUaLMv.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.xUaLMv.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az801-114:07934] *** Process received signal ***
[fv-az801-114:07934] Signal: Aborted (6)
[fv-az801-114:07934] Signal code:  (-6)
[fv-az801-114:07934] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6e71842520]
[fv-az801-114:07934] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6e718969fc]
[fv-az801-114:07934] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6e71842476]
[fv-az801-114:07934] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6e718287f3]
[fv-az801-114:07934] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6e71ca2b9e]
[fv-az801-114:07934] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6e71cae20c]
[fv-az801-114:07934] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6e71cae277]
[fv-az801-114:07934] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6e71cae52b]
[fv-az801-114:07934] [ 8] plumed(+0x14254)[0x5626e589c254]
[fv-az801-114:07934] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6e71829d90]
[fv-az801-114:07934] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6e71829e40]
[fv-az801-114:07934] [11] plumed(+0x14eb5)[0x5626e589ceb5]
[fv-az801-114:07934] *** End of error message ***
</pre>
{% endraw %}
