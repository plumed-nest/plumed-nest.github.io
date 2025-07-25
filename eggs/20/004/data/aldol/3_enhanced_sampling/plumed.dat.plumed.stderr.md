**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.DCiMTE.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.DCiMTE.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.DCiMTE.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.DCiMTE.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.DCiMTE.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmpptgkbjq6m:12579] *** Process received signal ***
[pkrvmpptgkbjq6m:12579] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12579] Signal code:  (-6)
[pkrvmpptgkbjq6m:12579] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe36c645330]
[pkrvmpptgkbjq6m:12579] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe36c69eb2c]
[pkrvmpptgkbjq6m:12579] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe36c64527e]
[pkrvmpptgkbjq6m:12579] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe36c6288ff]
[pkrvmpptgkbjq6m:12579] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe36caa5ff5]
[pkrvmpptgkbjq6m:12579] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe36cabb0da]
[pkrvmpptgkbjq6m:12579] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe36caa5a55]
[pkrvmpptgkbjq6m:12579] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe36caa5a6f]
[pkrvmpptgkbjq6m:12579] [ 8] plumed(+0x146dd)[0x55dc3565f6dd]
[pkrvmpptgkbjq6m:12579] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe36c62a1ca]
[pkrvmpptgkbjq6m:12579] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe36c62a28b]
[pkrvmpptgkbjq6m:12579] [11] plumed(+0x15365)[0x55dc35660365]
[pkrvmpptgkbjq6m:12579] *** End of error message ***
</pre>
{% endraw %}
