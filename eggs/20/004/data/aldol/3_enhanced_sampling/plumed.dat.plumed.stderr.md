**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.VkCHka.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.VkCHka.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.VkCHka.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.VkCHka.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.VkCHka.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:67728] *** Process received signal ***
[pkrvmbietmlfzoi:67728] Signal: Aborted (6)
[pkrvmbietmlfzoi:67728] Signal code:  (-6)
[pkrvmbietmlfzoi:67728] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb48a45330]
[pkrvmbietmlfzoi:67728] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb48a9eb2c]
[pkrvmbietmlfzoi:67728] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb48a4527e]
[pkrvmbietmlfzoi:67728] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb48a288ff]
[pkrvmbietmlfzoi:67728] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb48ea5ff5]
[pkrvmbietmlfzoi:67728] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb48ebb0da]
[pkrvmbietmlfzoi:67728] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb48ea5a55]
[pkrvmbietmlfzoi:67728] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb48ea5a6f]
[pkrvmbietmlfzoi:67728] [ 8] plumed(+0x146dd)[0x557d183b66dd]
[pkrvmbietmlfzoi:67728] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb48a2a1ca]
[pkrvmbietmlfzoi:67728] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb48a2a28b]
[pkrvmbietmlfzoi:67728] [11] plumed(+0x15365)[0x557d183b7365]
[pkrvmbietmlfzoi:67728] *** End of error message ***
</pre>
{% endraw %}
