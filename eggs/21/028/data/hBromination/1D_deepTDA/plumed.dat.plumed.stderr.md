**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.m2X7oh.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.m2X7oh.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.m2X7oh.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.m2X7oh.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.m2X7oh.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmq0rgcvqdmg:09166] *** Process received signal ***
[pkrvmq0rgcvqdmg:09166] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09166] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09166] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b7b645330]
[pkrvmq0rgcvqdmg:09166] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b7b69eb2c]
[pkrvmq0rgcvqdmg:09166] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b7b64527e]
[pkrvmq0rgcvqdmg:09166] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b7b6288ff]
[pkrvmq0rgcvqdmg:09166] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b7baa5ff5]
[pkrvmq0rgcvqdmg:09166] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b7babb0da]
[pkrvmq0rgcvqdmg:09166] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b7baa5a55]
[pkrvmq0rgcvqdmg:09166] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b7baa5a6f]
[pkrvmq0rgcvqdmg:09166] [ 8] plumed(+0x146dd)[0x559e7f49e6dd]
[pkrvmq0rgcvqdmg:09166] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b7b62a1ca]
[pkrvmq0rgcvqdmg:09166] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b7b62a28b]
[pkrvmq0rgcvqdmg:09166] [11] plumed(+0x15365)[0x559e7f49f365]
[pkrvmq0rgcvqdmg:09166] *** End of error message ***
</pre>
{% endraw %}
