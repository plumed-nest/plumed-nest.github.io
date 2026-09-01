**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.DHi8LZ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.DHi8LZ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.DHi8LZ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.DHi8LZ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.DHi8LZ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmgx7h7:10680] *** Process received signal ***
[runnervmgx7h7:10680] Signal: Aborted (6)
[runnervmgx7h7:10680] Signal code:  (-6)
[runnervmgx7h7:10680] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f81c2645330]
[runnervmgx7h7:10680] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f81c269ec0c]
[runnervmgx7h7:10680] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f81c264527e]
[runnervmgx7h7:10680] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f81c26288ff]
[runnervmgx7h7:10680] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81c2aa5ff5]
[runnervmgx7h7:10680] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81c2abb0da]
[runnervmgx7h7:10680] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81c2aa5a55]
[runnervmgx7h7:10680] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81c2aa5a6f]
[runnervmgx7h7:10680] [ 8] plumed(+0x146dd)[0x562a6cbf66dd]
[runnervmgx7h7:10680] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f81c262a1ca]
[runnervmgx7h7:10680] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f81c262a28b]
[runnervmgx7h7:10680] [11] plumed(+0x15365)[0x562a6cbf7365]
[runnervmgx7h7:10680] *** End of error message ***
</pre>
{% endraw %}
