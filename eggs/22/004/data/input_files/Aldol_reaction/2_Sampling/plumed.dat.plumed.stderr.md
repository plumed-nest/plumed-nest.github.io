**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.q4ewfi.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.q4ewfi.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.q4ewfi.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.q4ewfi.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.q4ewfi.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmi13qx:33052] *** Process received signal ***
[runnervmi13qx:33052] Signal: Aborted (6)
[runnervmi13qx:33052] Signal code:  (-6)
[runnervmi13qx:33052] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8844445330]
[runnervmi13qx:33052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f884449eb2c]
[runnervmi13qx:33052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f884444527e]
[runnervmi13qx:33052] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88444288ff]
[runnervmi13qx:33052] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88448a5ff5]
[runnervmi13qx:33052] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88448bb0da]
[runnervmi13qx:33052] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88448a5a55]
[runnervmi13qx:33052] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88448a5a6f]
[runnervmi13qx:33052] [ 8] plumed(+0x146dd)[0x55eb9891c6dd]
[runnervmi13qx:33052] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f884442a1ca]
[runnervmi13qx:33052] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f884442a28b]
[runnervmi13qx:33052] [11] plumed(+0x15365)[0x55eb9891d365]
[runnervmi13qx:33052] *** End of error message ***
</pre>
{% endraw %}
