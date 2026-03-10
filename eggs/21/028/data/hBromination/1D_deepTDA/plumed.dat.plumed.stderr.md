**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.wMYfI9.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.wMYfI9.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.wMYfI9.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.wMYfI9.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.wMYfI9.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervm0kj6c:10069] *** Process received signal ***
[runnervm0kj6c:10069] Signal: Aborted (6)
[runnervm0kj6c:10069] Signal code:  (-6)
[runnervm0kj6c:10069] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f564d445330]
[runnervm0kj6c:10069] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f564d49eb2c]
[runnervm0kj6c:10069] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f564d44527e]
[runnervm0kj6c:10069] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f564d4288ff]
[runnervm0kj6c:10069] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f564d8a5ff5]
[runnervm0kj6c:10069] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f564d8bb0da]
[runnervm0kj6c:10069] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f564d8a5a55]
[runnervm0kj6c:10069] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f564d8a5a6f]
[runnervm0kj6c:10069] [ 8] plumed(+0x146dd)[0x5626a86496dd]
[runnervm0kj6c:10069] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f564d42a1ca]
[runnervm0kj6c:10069] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f564d42a28b]
[runnervm0kj6c:10069] [11] plumed(+0x15365)[0x5626a864a365]
[runnervm0kj6c:10069] *** End of error message ***
</pre>
{% endraw %}
