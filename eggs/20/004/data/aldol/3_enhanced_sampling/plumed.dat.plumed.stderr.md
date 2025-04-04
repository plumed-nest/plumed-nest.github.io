**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.WgCB4u.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.WgCB4u.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.WgCB4u.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.WgCB4u.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.WgCB4u.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1624-565:10812] *** Process received signal ***
[fv-az1624-565:10812] Signal: Aborted (6)
[fv-az1624-565:10812] Signal code:  (-6)
[fv-az1624-565:10812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa1d1a45330]
[fv-az1624-565:10812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa1d1a9eb2c]
[fv-az1624-565:10812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa1d1a4527e]
[fv-az1624-565:10812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1d1a288ff]
[fv-az1624-565:10812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1d1ea5ff5]
[fv-az1624-565:10812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1d1ebb0da]
[fv-az1624-565:10812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1d1ea5a55]
[fv-az1624-565:10812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1d1ea5a6f]
[fv-az1624-565:10812] [ 8] plumed(+0x146dd)[0x55f0ca50d6dd]
[fv-az1624-565:10812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa1d1a2a1ca]
[fv-az1624-565:10812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa1d1a2a28b]
[fv-az1624-565:10812] [11] plumed(+0x15365)[0x55f0ca50e365]
[fv-az1624-565:10812] *** End of error message ***
</pre>
{% endraw %}
