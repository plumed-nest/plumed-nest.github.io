**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.xHe7oQ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.xHe7oQ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.xHe7oQ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.xHe7oQ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.xHe7oQ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmi13qx:39505] *** Process received signal ***
[runnervmi13qx:39505] Signal: Aborted (6)
[runnervmi13qx:39505] Signal code:  (-6)
[runnervmi13qx:39505] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffac6645330]
[runnervmi13qx:39505] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffac669eb2c]
[runnervmi13qx:39505] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffac664527e]
[runnervmi13qx:39505] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffac66288ff]
[runnervmi13qx:39505] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffac6aa5ff5]
[runnervmi13qx:39505] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffac6abb0da]
[runnervmi13qx:39505] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffac6aa5a55]
[runnervmi13qx:39505] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffac6aa5a6f]
[runnervmi13qx:39505] [ 8] plumed(+0x146dd)[0x557d6a5426dd]
[runnervmi13qx:39505] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffac662a1ca]
[runnervmi13qx:39505] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffac662a28b]
[runnervmi13qx:39505] [11] plumed(+0x15365)[0x557d6a543365]
[runnervmi13qx:39505] *** End of error message ***
</pre>
{% endraw %}
