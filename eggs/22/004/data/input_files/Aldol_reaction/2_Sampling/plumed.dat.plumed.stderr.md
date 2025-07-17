**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.pZnHFz.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.pZnHFz.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.pZnHFz.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.pZnHFz.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.pZnHFz.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmq0rgcvqdmg:09480] *** Process received signal ***
[pkrvmq0rgcvqdmg:09480] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09480] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe5d0a45330]
[pkrvmq0rgcvqdmg:09480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe5d0a9eb2c]
[pkrvmq0rgcvqdmg:09480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe5d0a4527e]
[pkrvmq0rgcvqdmg:09480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5d0a288ff]
[pkrvmq0rgcvqdmg:09480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5d0ea5ff5]
[pkrvmq0rgcvqdmg:09480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5d0ebb0da]
[pkrvmq0rgcvqdmg:09480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5d0ea5a55]
[pkrvmq0rgcvqdmg:09480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5d0ea5a6f]
[pkrvmq0rgcvqdmg:09480] [ 8] plumed(+0x146dd)[0x55f22fadb6dd]
[pkrvmq0rgcvqdmg:09480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe5d0a2a1ca]
[pkrvmq0rgcvqdmg:09480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe5d0a2a28b]
[pkrvmq0rgcvqdmg:09480] [11] plumed(+0x15365)[0x55f22fadc365]
[pkrvmq0rgcvqdmg:09480] *** End of error message ***
</pre>
{% endraw %}
