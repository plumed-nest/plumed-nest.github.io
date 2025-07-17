**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.zuIT2n.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.zuIT2n.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.zuIT2n.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.zuIT2n.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.zuIT2n.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmq0rgcvqdmg:11544] *** Process received signal ***
[pkrvmq0rgcvqdmg:11544] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11544] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11544] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2e12c45330]
[pkrvmq0rgcvqdmg:11544] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2e12c9eb2c]
[pkrvmq0rgcvqdmg:11544] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2e12c4527e]
[pkrvmq0rgcvqdmg:11544] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2e12c288ff]
[pkrvmq0rgcvqdmg:11544] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2e130a5ff5]
[pkrvmq0rgcvqdmg:11544] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2e130bb0da]
[pkrvmq0rgcvqdmg:11544] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2e130a5a55]
[pkrvmq0rgcvqdmg:11544] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2e130a5a6f]
[pkrvmq0rgcvqdmg:11544] [ 8] plumed(+0x146dd)[0x5576c94ee6dd]
[pkrvmq0rgcvqdmg:11544] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2e12c2a1ca]
[pkrvmq0rgcvqdmg:11544] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2e12c2a28b]
[pkrvmq0rgcvqdmg:11544] [11] plumed(+0x15365)[0x5576c94ef365]
[pkrvmq0rgcvqdmg:11544] *** End of error message ***
</pre>
{% endraw %}
