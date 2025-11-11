**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.SY6A02.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.SY6A02.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.SY6A02.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.SY6A02.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.SY6A02.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmw9dnm:10648] *** Process received signal ***
[runnervmw9dnm:10648] Signal: Aborted (6)
[runnervmw9dnm:10648] Signal code:  (-6)
[runnervmw9dnm:10648] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa307645330]
[runnervmw9dnm:10648] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa30769eb2c]
[runnervmw9dnm:10648] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa30764527e]
[runnervmw9dnm:10648] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3076288ff]
[runnervmw9dnm:10648] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa307aa5ff5]
[runnervmw9dnm:10648] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa307abb0da]
[runnervmw9dnm:10648] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa307aa5a55]
[runnervmw9dnm:10648] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa307aa5a6f]
[runnervmw9dnm:10648] [ 8] plumed(+0x146dd)[0x559b471a16dd]
[runnervmw9dnm:10648] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa30762a1ca]
[runnervmw9dnm:10648] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa30762a28b]
[runnervmw9dnm:10648] [11] plumed(+0x15365)[0x559b471a2365]
[runnervmw9dnm:10648] *** End of error message ***
</pre>
{% endraw %}
