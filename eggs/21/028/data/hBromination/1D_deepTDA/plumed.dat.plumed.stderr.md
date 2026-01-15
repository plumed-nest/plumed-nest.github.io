**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.tCWoqJ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.tCWoqJ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.tCWoqJ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.tCWoqJ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.tCWoqJ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmi13qx:35368] *** Process received signal ***
[runnervmi13qx:35368] Signal: Aborted (6)
[runnervmi13qx:35368] Signal code:  (-6)
[runnervmi13qx:35368] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f64bb845330]
[runnervmi13qx:35368] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f64bb89eb2c]
[runnervmi13qx:35368] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f64bb84527e]
[runnervmi13qx:35368] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64bb8288ff]
[runnervmi13qx:35368] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64bbca5ff5]
[runnervmi13qx:35368] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64bbcbb0da]
[runnervmi13qx:35368] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64bbca5a55]
[runnervmi13qx:35368] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64bbca5a6f]
[runnervmi13qx:35368] [ 8] plumed(+0x146dd)[0x55f8ec3316dd]
[runnervmi13qx:35368] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f64bb82a1ca]
[runnervmi13qx:35368] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f64bb82a28b]
[runnervmi13qx:35368] [11] plumed(+0x15365)[0x55f8ec332365]
[runnervmi13qx:35368] *** End of error message ***
</pre>
{% endraw %}
