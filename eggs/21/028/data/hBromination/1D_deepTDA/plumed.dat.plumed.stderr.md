**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.4Mj0RI.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.4Mj0RI.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.4Mj0RI.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.4Mj0RI.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.4Mj0RI.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:10720] *** Process received signal ***
[pkrvmbietmlfzoi:10720] Signal: Aborted (6)
[pkrvmbietmlfzoi:10720] Signal code:  (-6)
[pkrvmbietmlfzoi:10720] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc31d445330]
[pkrvmbietmlfzoi:10720] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc31d49eb2c]
[pkrvmbietmlfzoi:10720] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc31d44527e]
[pkrvmbietmlfzoi:10720] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc31d4288ff]
[pkrvmbietmlfzoi:10720] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc31d8a5ff5]
[pkrvmbietmlfzoi:10720] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc31d8bb0da]
[pkrvmbietmlfzoi:10720] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc31d8a5a55]
[pkrvmbietmlfzoi:10720] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc31d8a5a6f]
[pkrvmbietmlfzoi:10720] [ 8] plumed(+0x146dd)[0x559908e136dd]
[pkrvmbietmlfzoi:10720] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc31d42a1ca]
[pkrvmbietmlfzoi:10720] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc31d42a28b]
[pkrvmbietmlfzoi:10720] [11] plumed(+0x15365)[0x559908e14365]
[pkrvmbietmlfzoi:10720] *** End of error message ***
</pre>
{% endraw %}
