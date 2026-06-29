**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.zBbkiQ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.zBbkiQ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.zBbkiQ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.zBbkiQ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.zBbkiQ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmmklqx:07430] *** Process received signal ***
[runnervmmklqx:07430] Signal: Aborted (6)
[runnervmmklqx:07430] Signal code:  (-6)
[runnervmmklqx:07430] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f53ab045330]
[runnervmmklqx:07430] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f53ab09eb2c]
[runnervmmklqx:07430] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f53ab04527e]
[runnervmmklqx:07430] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53ab0288ff]
[runnervmmklqx:07430] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53ab4a5ff5]
[runnervmmklqx:07430] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53ab4bb0da]
[runnervmmklqx:07430] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53ab4a5a55]
[runnervmmklqx:07430] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53ab4a5a6f]
[runnervmmklqx:07430] [ 8] plumed(+0x146dd)[0x555e5c3e36dd]
[runnervmmklqx:07430] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f53ab02a1ca]
[runnervmmklqx:07430] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f53ab02a28b]
[runnervmmklqx:07430] [11] plumed(+0x15365)[0x555e5c3e4365]
[runnervmmklqx:07430] *** End of error message ***
</pre>
{% endraw %}
