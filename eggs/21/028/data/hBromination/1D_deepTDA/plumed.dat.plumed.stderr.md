**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.htoY1E.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.htoY1E.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.htoY1E.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.htoY1E.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.htoY1E.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvm7jw40e0xgp:12242] *** Process received signal ***
[pkrvm7jw40e0xgp:12242] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12242] Signal code:  (-6)
[pkrvm7jw40e0xgp:12242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5eb3845330]
[pkrvm7jw40e0xgp:12242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5eb389eb2c]
[pkrvm7jw40e0xgp:12242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5eb384527e]
[pkrvm7jw40e0xgp:12242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5eb38288ff]
[pkrvm7jw40e0xgp:12242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5eb3ca5ff5]
[pkrvm7jw40e0xgp:12242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5eb3cbb0da]
[pkrvm7jw40e0xgp:12242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5eb3ca5a55]
[pkrvm7jw40e0xgp:12242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5eb3ca5a6f]
[pkrvm7jw40e0xgp:12242] [ 8] plumed(+0x146dd)[0x5640137266dd]
[pkrvm7jw40e0xgp:12242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5eb382a1ca]
[pkrvm7jw40e0xgp:12242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5eb382a28b]
[pkrvm7jw40e0xgp:12242] [11] plumed(+0x15365)[0x564013727365]
[pkrvm7jw40e0xgp:12242] *** End of error message ***
</pre>
{% endraw %}
