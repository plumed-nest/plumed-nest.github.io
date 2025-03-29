**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.n0N83k.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.n0N83k.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.n0N83k.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.n0N83k.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.n0N83k.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az789-879:61998] *** Process received signal ***
[fv-az789-879:61998] Signal: Aborted (6)
[fv-az789-879:61998] Signal code:  (-6)
[fv-az789-879:61998] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff13c245330]
[fv-az789-879:61998] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff13c29eb2c]
[fv-az789-879:61998] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff13c24527e]
[fv-az789-879:61998] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff13c2288ff]
[fv-az789-879:61998] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff13c6a5ff5]
[fv-az789-879:61998] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff13c6bb0da]
[fv-az789-879:61998] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff13c6a5a55]
[fv-az789-879:61998] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff13c6a5a6f]
[fv-az789-879:61998] [ 8] plumed(+0x146dd)[0x556f778646dd]
[fv-az789-879:61998] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff13c22a1ca]
[fv-az789-879:61998] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff13c22a28b]
[fv-az789-879:61998] [11] plumed(+0x15365)[0x556f77865365]
[fv-az789-879:61998] *** End of error message ***
</pre>
{% endraw %}
