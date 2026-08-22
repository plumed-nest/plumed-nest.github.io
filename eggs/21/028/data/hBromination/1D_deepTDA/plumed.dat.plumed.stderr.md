**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.izSkjv.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.izSkjv.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.izSkjv.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.izSkjv.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.izSkjv.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervm76f27:09887] *** Process received signal ***
[runnervm76f27:09887] Signal: Aborted (6)
[runnervm76f27:09887] Signal code:  (-6)
[runnervm76f27:09887] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1809645330]
[runnervm76f27:09887] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f180969ec0c]
[runnervm76f27:09887] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f180964527e]
[runnervm76f27:09887] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f18096288ff]
[runnervm76f27:09887] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1809aa5ff5]
[runnervm76f27:09887] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1809abb0da]
[runnervm76f27:09887] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1809aa5a55]
[runnervm76f27:09887] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1809aa5a6f]
[runnervm76f27:09887] [ 8] plumed(+0x146dd)[0x556bc90136dd]
[runnervm76f27:09887] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f180962a1ca]
[runnervm76f27:09887] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f180962a28b]
[runnervm76f27:09887] [11] plumed(+0x15365)[0x556bc9014365]
[runnervm76f27:09887] *** End of error message ***
</pre>
{% endraw %}
