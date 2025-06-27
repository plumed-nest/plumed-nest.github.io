**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.bf54K5.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.bf54K5.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.bf54K5.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.bf54K5.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.bf54K5.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:66532] *** Process received signal ***
[pkrvmbietmlfzoi:66532] Signal: Aborted (6)
[pkrvmbietmlfzoi:66532] Signal code:  (-6)
[pkrvmbietmlfzoi:66532] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e2cc45330]
[pkrvmbietmlfzoi:66532] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e2cc9eb2c]
[pkrvmbietmlfzoi:66532] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e2cc4527e]
[pkrvmbietmlfzoi:66532] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e2cc288ff]
[pkrvmbietmlfzoi:66532] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e2d0a5ff5]
[pkrvmbietmlfzoi:66532] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e2d0bb0da]
[pkrvmbietmlfzoi:66532] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e2d0a5a55]
[pkrvmbietmlfzoi:66532] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e2d0a5a6f]
[pkrvmbietmlfzoi:66532] [ 8] plumed(+0x146dd)[0x55b1273576dd]
[pkrvmbietmlfzoi:66532] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e2cc2a1ca]
[pkrvmbietmlfzoi:66532] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e2cc2a28b]
[pkrvmbietmlfzoi:66532] [11] plumed(+0x15365)[0x55b127358365]
[pkrvmbietmlfzoi:66532] *** End of error message ***
</pre>
{% endraw %}
