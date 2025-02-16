**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.gHKhRD.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.gHKhRD.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.gHKhRD.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.gHKhRD.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.gHKhRD.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1937-158:64515] *** Process received signal ***
[fv-az1937-158:64515] Signal: Aborted (6)
[fv-az1937-158:64515] Signal code:  (-6)
[fv-az1937-158:64515] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb431a45330]
[fv-az1937-158:64515] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb431a9eb2c]
[fv-az1937-158:64515] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb431a4527e]
[fv-az1937-158:64515] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb431a288ff]
[fv-az1937-158:64515] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb431ea5ff5]
[fv-az1937-158:64515] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb431ebb0da]
[fv-az1937-158:64515] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb431ea5a55]
[fv-az1937-158:64515] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb431ea5a6f]
[fv-az1937-158:64515] [ 8] plumed(+0x146dd)[0x560a2e33a6dd]
[fv-az1937-158:64515] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb431a2a1ca]
[fv-az1937-158:64515] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb431a2a28b]
[fv-az1937-158:64515] [11] plumed(+0x15365)[0x560a2e33b365]
[fv-az1937-158:64515] *** End of error message ***
</pre>
{% endraw %}
