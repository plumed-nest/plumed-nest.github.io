**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.c12HHz.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.c12HHz.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.c12HHz.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.c12HHz.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.c12HHz.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:67376] *** Process received signal ***
[pkrvmbietmlfzoi:67376] Signal: Aborted (6)
[pkrvmbietmlfzoi:67376] Signal code:  (-6)
[pkrvmbietmlfzoi:67376] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd296445330]
[pkrvmbietmlfzoi:67376] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd29649eb2c]
[pkrvmbietmlfzoi:67376] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd29644527e]
[pkrvmbietmlfzoi:67376] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2964288ff]
[pkrvmbietmlfzoi:67376] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2968a5ff5]
[pkrvmbietmlfzoi:67376] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2968bb0da]
[pkrvmbietmlfzoi:67376] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2968a5a55]
[pkrvmbietmlfzoi:67376] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2968a5a6f]
[pkrvmbietmlfzoi:67376] [ 8] plumed(+0x146dd)[0x561f4c2066dd]
[pkrvmbietmlfzoi:67376] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd29642a1ca]
[pkrvmbietmlfzoi:67376] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd29642a28b]
[pkrvmbietmlfzoi:67376] [11] plumed(+0x15365)[0x561f4c207365]
[pkrvmbietmlfzoi:67376] *** End of error message ***
</pre>
{% endraw %}
