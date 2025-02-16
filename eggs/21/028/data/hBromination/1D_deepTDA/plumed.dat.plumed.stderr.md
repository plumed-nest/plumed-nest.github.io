**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.qUZpCL.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.qUZpCL.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.qUZpCL.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.qUZpCL.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.qUZpCL.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az787-589:63999] *** Process received signal ***
[fv-az787-589:63999] Signal: Aborted (6)
[fv-az787-589:63999] Signal code:  (-6)
[fv-az787-589:63999] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc34b445330]
[fv-az787-589:63999] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc34b49eb2c]
[fv-az787-589:63999] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc34b44527e]
[fv-az787-589:63999] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc34b4288ff]
[fv-az787-589:63999] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc34b8a5ff5]
[fv-az787-589:63999] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc34b8bb0da]
[fv-az787-589:63999] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc34b8a5a55]
[fv-az787-589:63999] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc34b8a5a6f]
[fv-az787-589:63999] [ 8] plumed(+0x146dd)[0x55b6b92386dd]
[fv-az787-589:63999] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc34b42a1ca]
[fv-az787-589:63999] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc34b42a28b]
[fv-az787-589:63999] [11] plumed(+0x15365)[0x55b6b9239365]
[fv-az787-589:63999] *** End of error message ***
</pre>
{% endraw %}
