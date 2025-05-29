**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.6PtxWh.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.6PtxWh.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.6PtxWh.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.6PtxWh.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.6PtxWh.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmf6wy0o8zjz:64177] *** Process received signal ***
[pkrvmf6wy0o8zjz:64177] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64177] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64177] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f37cdc45330]
[pkrvmf6wy0o8zjz:64177] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f37cdc9eb2c]
[pkrvmf6wy0o8zjz:64177] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f37cdc4527e]
[pkrvmf6wy0o8zjz:64177] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f37cdc288ff]
[pkrvmf6wy0o8zjz:64177] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37ce0a5ff5]
[pkrvmf6wy0o8zjz:64177] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37ce0bb0da]
[pkrvmf6wy0o8zjz:64177] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37ce0a5a55]
[pkrvmf6wy0o8zjz:64177] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37ce0a5a6f]
[pkrvmf6wy0o8zjz:64177] [ 8] plumed(+0x146dd)[0x5568420926dd]
[pkrvmf6wy0o8zjz:64177] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f37cdc2a1ca]
[pkrvmf6wy0o8zjz:64177] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f37cdc2a28b]
[pkrvmf6wy0o8zjz:64177] [11] plumed(+0x15365)[0x556842093365]
[pkrvmf6wy0o8zjz:64177] *** End of error message ***
</pre>
{% endraw %}
