**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.Te6m94.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.Te6m94.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.Te6m94.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.Te6m94.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.Te6m94.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmxyh4eaekms:09025] *** Process received signal ***
[pkrvmxyh4eaekms:09025] Signal: Aborted (6)
[pkrvmxyh4eaekms:09025] Signal code:  (-6)
[pkrvmxyh4eaekms:09025] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2595445330]
[pkrvmxyh4eaekms:09025] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f259549eb2c]
[pkrvmxyh4eaekms:09025] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f259544527e]
[pkrvmxyh4eaekms:09025] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25954288ff]
[pkrvmxyh4eaekms:09025] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f25958a5ff5]
[pkrvmxyh4eaekms:09025] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f25958bb0da]
[pkrvmxyh4eaekms:09025] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f25958a5a55]
[pkrvmxyh4eaekms:09025] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f25958a5a6f]
[pkrvmxyh4eaekms:09025] [ 8] plumed(+0x146dd)[0x55f942d086dd]
[pkrvmxyh4eaekms:09025] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f259542a1ca]
[pkrvmxyh4eaekms:09025] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f259542a28b]
[pkrvmxyh4eaekms:09025] [11] plumed(+0x15365)[0x55f942d09365]
[pkrvmxyh4eaekms:09025] *** End of error message ***
</pre>
{% endraw %}
