**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.Ib40yY.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.Ib40yY.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.Ib40yY.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.Ib40yY.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.Ib40yY.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmxyh4eaekms:11131] *** Process received signal ***
[pkrvmxyh4eaekms:11131] Signal: Aborted (6)
[pkrvmxyh4eaekms:11131] Signal code:  (-6)
[pkrvmxyh4eaekms:11131] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc38c445330]
[pkrvmxyh4eaekms:11131] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc38c49eb2c]
[pkrvmxyh4eaekms:11131] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc38c44527e]
[pkrvmxyh4eaekms:11131] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc38c4288ff]
[pkrvmxyh4eaekms:11131] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc38c8a5ff5]
[pkrvmxyh4eaekms:11131] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc38c8bb0da]
[pkrvmxyh4eaekms:11131] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc38c8a5a55]
[pkrvmxyh4eaekms:11131] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc38c8a5a6f]
[pkrvmxyh4eaekms:11131] [ 8] plumed(+0x146dd)[0x55d0bd7fa6dd]
[pkrvmxyh4eaekms:11131] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc38c42a1ca]
[pkrvmxyh4eaekms:11131] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc38c42a28b]
[pkrvmxyh4eaekms:11131] [11] plumed(+0x15365)[0x55d0bd7fb365]
[pkrvmxyh4eaekms:11131] *** End of error message ***
</pre>
{% endraw %}
