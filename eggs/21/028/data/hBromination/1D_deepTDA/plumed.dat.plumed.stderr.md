**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.gXknAQ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.gXknAQ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.gXknAQ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.gXknAQ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.gXknAQ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmxyh4eaekms:09133] *** Process received signal ***
[pkrvmxyh4eaekms:09133] Signal: Aborted (6)
[pkrvmxyh4eaekms:09133] Signal code:  (-6)
[pkrvmxyh4eaekms:09133] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8cbcc45330]
[pkrvmxyh4eaekms:09133] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8cbcc9eb2c]
[pkrvmxyh4eaekms:09133] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8cbcc4527e]
[pkrvmxyh4eaekms:09133] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8cbcc288ff]
[pkrvmxyh4eaekms:09133] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8cbd0a5ff5]
[pkrvmxyh4eaekms:09133] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8cbd0bb0da]
[pkrvmxyh4eaekms:09133] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8cbd0a5a55]
[pkrvmxyh4eaekms:09133] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8cbd0a5a6f]
[pkrvmxyh4eaekms:09133] [ 8] plumed(+0x146dd)[0x55e7efb5e6dd]
[pkrvmxyh4eaekms:09133] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8cbcc2a1ca]
[pkrvmxyh4eaekms:09133] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8cbcc2a28b]
[pkrvmxyh4eaekms:09133] [11] plumed(+0x15365)[0x55e7efb5f365]
[pkrvmxyh4eaekms:09133] *** End of error message ***
</pre>
{% endraw %}
