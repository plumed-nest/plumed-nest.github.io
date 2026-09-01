**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.zCBxxb.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.zCBxxb.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.zCBxxb.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.zCBxxb.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.zCBxxb.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmgx7h7:08187] *** Process received signal ***
[runnervmgx7h7:08187] Signal: Aborted (6)
[runnervmgx7h7:08187] Signal code:  (-6)
[runnervmgx7h7:08187] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f82cb445330]
[runnervmgx7h7:08187] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f82cb49ec0c]
[runnervmgx7h7:08187] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f82cb44527e]
[runnervmgx7h7:08187] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82cb4288ff]
[runnervmgx7h7:08187] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82cb8a5ff5]
[runnervmgx7h7:08187] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82cb8bb0da]
[runnervmgx7h7:08187] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82cb8a5a55]
[runnervmgx7h7:08187] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82cb8a5a6f]
[runnervmgx7h7:08187] [ 8] plumed(+0x146dd)[0x563ff85236dd]
[runnervmgx7h7:08187] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f82cb42a1ca]
[runnervmgx7h7:08187] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f82cb42a28b]
[runnervmgx7h7:08187] [11] plumed(+0x15365)[0x563ff8524365]
[runnervmgx7h7:08187] *** End of error message ***
</pre>
{% endraw %}
