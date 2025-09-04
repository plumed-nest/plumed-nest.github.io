**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.rTDhJY.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.rTDhJY.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.rTDhJY.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.rTDhJY.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.rTDhJY.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvm7jw40e0xgp:11116] *** Process received signal ***
[pkrvm7jw40e0xgp:11116] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11116] Signal code:  (-6)
[pkrvm7jw40e0xgp:11116] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6083645330]
[pkrvm7jw40e0xgp:11116] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f608369eb2c]
[pkrvm7jw40e0xgp:11116] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f608364527e]
[pkrvm7jw40e0xgp:11116] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f60836288ff]
[pkrvm7jw40e0xgp:11116] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6083aa5ff5]
[pkrvm7jw40e0xgp:11116] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6083abb0da]
[pkrvm7jw40e0xgp:11116] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6083aa5a55]
[pkrvm7jw40e0xgp:11116] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6083aa5a6f]
[pkrvm7jw40e0xgp:11116] [ 8] plumed(+0x146dd)[0x55e02df446dd]
[pkrvm7jw40e0xgp:11116] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f608362a1ca]
[pkrvm7jw40e0xgp:11116] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f608362a28b]
[pkrvm7jw40e0xgp:11116] [11] plumed(+0x15365)[0x55e02df45365]
[pkrvm7jw40e0xgp:11116] *** End of error message ***
</pre>
{% endraw %}
