**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.cN9Z7B.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.cN9Z7B.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.cN9Z7B.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.cN9Z7B.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.cN9Z7B.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1390-170:06526] *** Process received signal ***
[fv-az1390-170:06526] Signal: Aborted (6)
[fv-az1390-170:06526] Signal code:  (-6)
[fv-az1390-170:06526] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac16445330]
[fv-az1390-170:06526] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac1649eb2c]
[fv-az1390-170:06526] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac1644527e]
[fv-az1390-170:06526] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac164288ff]
[fv-az1390-170:06526] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac168a5ff5]
[fv-az1390-170:06526] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac168bb0da]
[fv-az1390-170:06526] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac168a5a55]
[fv-az1390-170:06526] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac168a5a6f]
[fv-az1390-170:06526] [ 8] plumed(+0x146dd)[0x55de309dd6dd]
[fv-az1390-170:06526] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac1642a1ca]
[fv-az1390-170:06526] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac1642a28b]
[fv-az1390-170:06526] [11] plumed(+0x15365)[0x55de309de365]
[fv-az1390-170:06526] *** End of error message ***
</pre>
{% endraw %}
