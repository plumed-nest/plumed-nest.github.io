**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.o8vUQN.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.o8vUQN.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.o8vUQN.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.o8vUQN.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.o8vUQN.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmkj6or:06331] *** Process received signal ***
[runnervmkj6or:06331] Signal: Aborted (6)
[runnervmkj6or:06331] Signal code:  (-6)
[runnervmkj6or:06331] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7440645330]
[runnervmkj6or:06331] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f744069eb2c]
[runnervmkj6or:06331] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f744064527e]
[runnervmkj6or:06331] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f74406288ff]
[runnervmkj6or:06331] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7440aa5ff5]
[runnervmkj6or:06331] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7440abb0da]
[runnervmkj6or:06331] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7440aa5a55]
[runnervmkj6or:06331] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7440aa5a6f]
[runnervmkj6or:06331] [ 8] plumed(+0x146dd)[0x555d411ea6dd]
[runnervmkj6or:06331] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f744062a1ca]
[runnervmkj6or:06331] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f744062a28b]
[runnervmkj6or:06331] [11] plumed(+0x15365)[0x555d411eb365]
[runnervmkj6or:06331] *** End of error message ***
</pre>
{% endraw %}
