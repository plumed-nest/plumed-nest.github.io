**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.Ph0hun.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.Ph0hun.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.Ph0hun.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.Ph0hun.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.Ph0hun.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmw9dnm:08842] *** Process received signal ***
[runnervmw9dnm:08842] Signal: Aborted (6)
[runnervmw9dnm:08842] Signal code:  (-6)
[runnervmw9dnm:08842] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde23445330]
[runnervmw9dnm:08842] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde2349eb2c]
[runnervmw9dnm:08842] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde2344527e]
[runnervmw9dnm:08842] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde234288ff]
[runnervmw9dnm:08842] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde238a5ff5]
[runnervmw9dnm:08842] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde238bb0da]
[runnervmw9dnm:08842] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde238a5a55]
[runnervmw9dnm:08842] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde238a5a6f]
[runnervmw9dnm:08842] [ 8] plumed(+0x146dd)[0x564471fea6dd]
[runnervmw9dnm:08842] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde2342a1ca]
[runnervmw9dnm:08842] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde2342a28b]
[runnervmw9dnm:08842] [11] plumed(+0x15365)[0x564471feb365]
[runnervmw9dnm:08842] *** End of error message ***
</pre>
{% endraw %}
