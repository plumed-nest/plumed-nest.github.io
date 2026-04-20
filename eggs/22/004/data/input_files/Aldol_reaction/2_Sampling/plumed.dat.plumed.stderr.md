**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.CuKXI6.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.CuKXI6.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.CuKXI6.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.CuKXI6.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.CuKXI6.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmeorf1:07015] *** Process received signal ***
[runnervmeorf1:07015] Signal: Aborted (6)
[runnervmeorf1:07015] Signal code:  (-6)
[runnervmeorf1:07015] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79e7a45330]
[runnervmeorf1:07015] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79e7a9eb2c]
[runnervmeorf1:07015] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79e7a4527e]
[runnervmeorf1:07015] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79e7a288ff]
[runnervmeorf1:07015] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79e7ea5ff5]
[runnervmeorf1:07015] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79e7ebb0da]
[runnervmeorf1:07015] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79e7ea5a55]
[runnervmeorf1:07015] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79e7ea5a6f]
[runnervmeorf1:07015] [ 8] plumed(+0x146dd)[0x5618473d36dd]
[runnervmeorf1:07015] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79e7a2a1ca]
[runnervmeorf1:07015] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79e7a2a28b]
[runnervmeorf1:07015] [11] plumed(+0x15365)[0x5618473d4365]
[runnervmeorf1:07015] *** End of error message ***
</pre>
{% endraw %}
