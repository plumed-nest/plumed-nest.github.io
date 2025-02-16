**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.JMdzyL.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.JMdzyL.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.JMdzyL.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.JMdzyL.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.JMdzyL.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1112-175:67709] *** Process received signal ***
[fv-az1112-175:67709] Signal: Aborted (6)
[fv-az1112-175:67709] Signal code:  (-6)
[fv-az1112-175:67709] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe811645330]
[fv-az1112-175:67709] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe81169eb2c]
[fv-az1112-175:67709] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe81164527e]
[fv-az1112-175:67709] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8116288ff]
[fv-az1112-175:67709] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe811aa5ff5]
[fv-az1112-175:67709] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe811abb0da]
[fv-az1112-175:67709] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe811aa5a55]
[fv-az1112-175:67709] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe811aa5a6f]
[fv-az1112-175:67709] [ 8] plumed(+0x146dd)[0x5593216fa6dd]
[fv-az1112-175:67709] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe81162a1ca]
[fv-az1112-175:67709] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe81162a28b]
[fv-az1112-175:67709] [11] plumed(+0x15365)[0x5593216fb365]
[fv-az1112-175:67709] *** End of error message ***
</pre>
{% endraw %}
