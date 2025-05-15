**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.EO5k2h.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.EO5k2h.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.EO5k2h.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.EO5k2h.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.EO5k2h.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmberfyhpb9w:08048] *** Process received signal ***
[pkrvmberfyhpb9w:08048] Signal: Aborted (6)
[pkrvmberfyhpb9w:08048] Signal code:  (-6)
[pkrvmberfyhpb9w:08048] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ec4645330]
[pkrvmberfyhpb9w:08048] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ec469eb2c]
[pkrvmberfyhpb9w:08048] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ec464527e]
[pkrvmberfyhpb9w:08048] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ec46288ff]
[pkrvmberfyhpb9w:08048] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ec4aa5ff5]
[pkrvmberfyhpb9w:08048] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ec4abb0da]
[pkrvmberfyhpb9w:08048] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ec4aa5a55]
[pkrvmberfyhpb9w:08048] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ec4aa5a6f]
[pkrvmberfyhpb9w:08048] [ 8] plumed(+0x146dd)[0x556eaf7c76dd]
[pkrvmberfyhpb9w:08048] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ec462a1ca]
[pkrvmberfyhpb9w:08048] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ec462a28b]
[pkrvmberfyhpb9w:08048] [11] plumed(+0x15365)[0x556eaf7c8365]
[pkrvmberfyhpb9w:08048] *** End of error message ***
</pre>
{% endraw %}
