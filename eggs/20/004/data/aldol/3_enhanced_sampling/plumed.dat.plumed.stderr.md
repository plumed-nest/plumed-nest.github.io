**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.snF0vX.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.snF0vX.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.snF0vX.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.snF0vX.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.snF0vX.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:11371] *** Process received signal ***
[pkrvmbietmlfzoi:11371] Signal: Aborted (6)
[pkrvmbietmlfzoi:11371] Signal code:  (-6)
[pkrvmbietmlfzoi:11371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe259a45330]
[pkrvmbietmlfzoi:11371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe259a9eb2c]
[pkrvmbietmlfzoi:11371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe259a4527e]
[pkrvmbietmlfzoi:11371] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe259a288ff]
[pkrvmbietmlfzoi:11371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe259ea5ff5]
[pkrvmbietmlfzoi:11371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe259ebb0da]
[pkrvmbietmlfzoi:11371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe259ea5a55]
[pkrvmbietmlfzoi:11371] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe259ea5a6f]
[pkrvmbietmlfzoi:11371] [ 8] plumed(+0x146dd)[0x55c716e586dd]
[pkrvmbietmlfzoi:11371] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe259a2a1ca]
[pkrvmbietmlfzoi:11371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe259a2a28b]
[pkrvmbietmlfzoi:11371] [11] plumed(+0x15365)[0x55c716e59365]
[pkrvmbietmlfzoi:11371] *** End of error message ***
</pre>
{% endraw %}
