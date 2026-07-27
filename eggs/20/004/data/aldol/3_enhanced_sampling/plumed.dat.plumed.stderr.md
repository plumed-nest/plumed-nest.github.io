**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.HQ2Zmx.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.HQ2Zmx.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.HQ2Zmx.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.HQ2Zmx.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.HQ2Zmx.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmvrwv9:09806] *** Process received signal ***
[runnervmvrwv9:09806] Signal: Aborted (6)
[runnervmvrwv9:09806] Signal code:  (-6)
[runnervmvrwv9:09806] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1cc3045330]
[runnervmvrwv9:09806] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1cc309eb2c]
[runnervmvrwv9:09806] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1cc304527e]
[runnervmvrwv9:09806] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1cc30288ff]
[runnervmvrwv9:09806] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1cc34a5ff5]
[runnervmvrwv9:09806] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1cc34bb0da]
[runnervmvrwv9:09806] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1cc34a5a55]
[runnervmvrwv9:09806] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1cc34a5a6f]
[runnervmvrwv9:09806] [ 8] plumed(+0x146dd)[0x565077f226dd]
[runnervmvrwv9:09806] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1cc302a1ca]
[runnervmvrwv9:09806] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1cc302a28b]
[runnervmvrwv9:09806] [11] plumed(+0x15365)[0x565077f23365]
[runnervmvrwv9:09806] *** End of error message ***
</pre>
{% endraw %}
