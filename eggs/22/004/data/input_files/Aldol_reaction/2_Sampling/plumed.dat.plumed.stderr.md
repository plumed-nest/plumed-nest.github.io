**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.ppDjhE.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.ppDjhE.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.ppDjhE.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.ppDjhE.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.ppDjhE.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmpptgkbjq6m:09036] *** Process received signal ***
[pkrvmpptgkbjq6m:09036] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09036] Signal code:  (-6)
[pkrvmpptgkbjq6m:09036] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab67045330]
[pkrvmpptgkbjq6m:09036] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab6709eb2c]
[pkrvmpptgkbjq6m:09036] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab6704527e]
[pkrvmpptgkbjq6m:09036] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab670288ff]
[pkrvmpptgkbjq6m:09036] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab674a5ff5]
[pkrvmpptgkbjq6m:09036] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab674bb0da]
[pkrvmpptgkbjq6m:09036] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab674a5a55]
[pkrvmpptgkbjq6m:09036] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab674a5a6f]
[pkrvmpptgkbjq6m:09036] [ 8] plumed(+0x146dd)[0x558e982736dd]
[pkrvmpptgkbjq6m:09036] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab6702a1ca]
[pkrvmpptgkbjq6m:09036] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab6702a28b]
[pkrvmpptgkbjq6m:09036] [11] plumed(+0x15365)[0x558e98274365]
[pkrvmpptgkbjq6m:09036] *** End of error message ***
</pre>
{% endraw %}
