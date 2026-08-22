**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.uu4lQd.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.uu4lQd.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.uu4lQd.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.uu4lQd.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.uu4lQd.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervm76f27:07728] *** Process received signal ***
[runnervm76f27:07728] Signal: Aborted (6)
[runnervm76f27:07728] Signal code:  (-6)
[runnervm76f27:07728] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fafda445330]
[runnervm76f27:07728] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fafda49ec0c]
[runnervm76f27:07728] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fafda44527e]
[runnervm76f27:07728] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fafda4288ff]
[runnervm76f27:07728] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fafda8a5ff5]
[runnervm76f27:07728] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fafda8bb0da]
[runnervm76f27:07728] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fafda8a5a55]
[runnervm76f27:07728] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fafda8a5a6f]
[runnervm76f27:07728] [ 8] plumed(+0x146dd)[0x561887c056dd]
[runnervm76f27:07728] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fafda42a1ca]
[runnervm76f27:07728] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fafda42a28b]
[runnervm76f27:07728] [11] plumed(+0x15365)[0x561887c06365]
[runnervm76f27:07728] *** End of error message ***
</pre>
{% endraw %}
