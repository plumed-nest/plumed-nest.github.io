**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.R41Yjf.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.R41Yjf.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.R41Yjf.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.R41Yjf.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.R41Yjf.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmw9dnm:10384] *** Process received signal ***
[runnervmw9dnm:10384] Signal: Aborted (6)
[runnervmw9dnm:10384] Signal code:  (-6)
[runnervmw9dnm:10384] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9140c45330]
[runnervmw9dnm:10384] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9140c9eb2c]
[runnervmw9dnm:10384] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9140c4527e]
[runnervmw9dnm:10384] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9140c288ff]
[runnervmw9dnm:10384] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91410a5ff5]
[runnervmw9dnm:10384] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91410bb0da]
[runnervmw9dnm:10384] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91410a5a55]
[runnervmw9dnm:10384] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91410a5a6f]
[runnervmw9dnm:10384] [ 8] plumed(+0x146dd)[0x559ba27f56dd]
[runnervmw9dnm:10384] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9140c2a1ca]
[runnervmw9dnm:10384] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9140c2a28b]
[runnervmw9dnm:10384] [11] plumed(+0x15365)[0x559ba27f6365]
[runnervmw9dnm:10384] *** End of error message ***
</pre>
{% endraw %}
