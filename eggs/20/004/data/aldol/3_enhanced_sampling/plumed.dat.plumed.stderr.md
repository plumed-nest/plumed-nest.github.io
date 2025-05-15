**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.knHyKm.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.knHyKm.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.knHyKm.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.knHyKm.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.knHyKm.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmberfyhpb9w:10147] *** Process received signal ***
[pkrvmberfyhpb9w:10147] Signal: Aborted (6)
[pkrvmberfyhpb9w:10147] Signal code:  (-6)
[pkrvmberfyhpb9w:10147] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19bfc45330]
[pkrvmberfyhpb9w:10147] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19bfc9eb2c]
[pkrvmberfyhpb9w:10147] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19bfc4527e]
[pkrvmberfyhpb9w:10147] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19bfc288ff]
[pkrvmberfyhpb9w:10147] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19c00a5ff5]
[pkrvmberfyhpb9w:10147] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19c00bb0da]
[pkrvmberfyhpb9w:10147] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19c00a5a55]
[pkrvmberfyhpb9w:10147] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19c00a5a6f]
[pkrvmberfyhpb9w:10147] [ 8] plumed(+0x146dd)[0x558aacdc16dd]
[pkrvmberfyhpb9w:10147] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19bfc2a1ca]
[pkrvmberfyhpb9w:10147] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19bfc2a28b]
[pkrvmberfyhpb9w:10147] [11] plumed(+0x15365)[0x558aacdc2365]
[pkrvmberfyhpb9w:10147] *** End of error message ***
</pre>
{% endraw %}
