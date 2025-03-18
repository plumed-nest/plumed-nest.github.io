**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.V52eZC.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.V52eZC.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.V52eZC.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.V52eZC.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.V52eZC.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1267-279:64702] *** Process received signal ***
[fv-az1267-279:64702] Signal: Aborted (6)
[fv-az1267-279:64702] Signal code:  (-6)
[fv-az1267-279:64702] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6af7a45330]
[fv-az1267-279:64702] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6af7a9eb2c]
[fv-az1267-279:64702] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6af7a4527e]
[fv-az1267-279:64702] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6af7a288ff]
[fv-az1267-279:64702] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6af7ea5ff5]
[fv-az1267-279:64702] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6af7ebb0da]
[fv-az1267-279:64702] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6af7ea5a55]
[fv-az1267-279:64702] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6af7ea5a6f]
[fv-az1267-279:64702] [ 8] plumed(+0x146dd)[0x5618650696dd]
[fv-az1267-279:64702] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6af7a2a1ca]
[fv-az1267-279:64702] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6af7a2a28b]
[fv-az1267-279:64702] [11] plumed(+0x15365)[0x56186506a365]
[fv-az1267-279:64702] *** End of error message ***
</pre>
{% endraw %}
