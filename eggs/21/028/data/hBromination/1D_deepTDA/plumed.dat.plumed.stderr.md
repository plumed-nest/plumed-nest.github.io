**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.cwsJEc.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.cwsJEc.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.cwsJEc.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.cwsJEc.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.cwsJEc.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmpptgkbjq6m:10343] *** Process received signal ***
[pkrvmpptgkbjq6m:10343] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10343] Signal code:  (-6)
[pkrvmpptgkbjq6m:10343] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b36845330]
[pkrvmpptgkbjq6m:10343] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b3689eb2c]
[pkrvmpptgkbjq6m:10343] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b3684527e]
[pkrvmpptgkbjq6m:10343] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b368288ff]
[pkrvmpptgkbjq6m:10343] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b36ca5ff5]
[pkrvmpptgkbjq6m:10343] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b36cbb0da]
[pkrvmpptgkbjq6m:10343] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b36ca5a55]
[pkrvmpptgkbjq6m:10343] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b36ca5a6f]
[pkrvmpptgkbjq6m:10343] [ 8] plumed(+0x146dd)[0x559bd2bfc6dd]
[pkrvmpptgkbjq6m:10343] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b3682a1ca]
[pkrvmpptgkbjq6m:10343] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b3682a28b]
[pkrvmpptgkbjq6m:10343] [11] plumed(+0x15365)[0x559bd2bfd365]
[pkrvmpptgkbjq6m:10343] *** End of error message ***
</pre>
{% endraw %}
