**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.4EvufQ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.4EvufQ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.4EvufQ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.4EvufQ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.4EvufQ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1719-82:68443] *** Process received signal ***
[fv-az1719-82:68443] Signal: Aborted (6)
[fv-az1719-82:68443] Signal code:  (-6)
[fv-az1719-82:68443] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa9c7245330]
[fv-az1719-82:68443] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa9c729eb2c]
[fv-az1719-82:68443] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa9c724527e]
[fv-az1719-82:68443] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9c72288ff]
[fv-az1719-82:68443] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa9c76a5ff5]
[fv-az1719-82:68443] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa9c76bb0da]
[fv-az1719-82:68443] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa9c76a5a55]
[fv-az1719-82:68443] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa9c76a5a6f]
[fv-az1719-82:68443] [ 8] plumed(+0x146dd)[0x55dcbb2856dd]
[fv-az1719-82:68443] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa9c722a1ca]
[fv-az1719-82:68443] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa9c722a28b]
[fv-az1719-82:68443] [11] plumed(+0x15365)[0x55dcbb286365]
[fv-az1719-82:68443] *** End of error message ***
</pre>
{% endraw %}
