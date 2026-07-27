**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.GTcmub.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.GTcmub.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.GTcmub.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.GTcmub.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.GTcmub.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmvrwv9:10310] *** Process received signal ***
[runnervmvrwv9:10310] Signal: Aborted (6)
[runnervmvrwv9:10310] Signal code:  (-6)
[runnervmvrwv9:10310] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8be8c45330]
[runnervmvrwv9:10310] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8be8c9eb2c]
[runnervmvrwv9:10310] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8be8c4527e]
[runnervmvrwv9:10310] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8be8c288ff]
[runnervmvrwv9:10310] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8be90a5ff5]
[runnervmvrwv9:10310] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8be90bb0da]
[runnervmvrwv9:10310] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8be90a5a55]
[runnervmvrwv9:10310] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8be90a5a6f]
[runnervmvrwv9:10310] [ 8] plumed(+0x146dd)[0x56457aadf6dd]
[runnervmvrwv9:10310] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8be8c2a1ca]
[runnervmvrwv9:10310] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8be8c2a28b]
[runnervmvrwv9:10310] [11] plumed(+0x15365)[0x56457aae0365]
[runnervmvrwv9:10310] *** End of error message ***
</pre>
{% endraw %}
