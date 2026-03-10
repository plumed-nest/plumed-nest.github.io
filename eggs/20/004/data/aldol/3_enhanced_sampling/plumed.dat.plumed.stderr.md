**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.JjtXNZ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.JjtXNZ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.JjtXNZ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.JjtXNZ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.JjtXNZ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervm0kj6c:08488] *** Process received signal ***
[runnervm0kj6c:08488] Signal: Aborted (6)
[runnervm0kj6c:08488] Signal code:  (-6)
[runnervm0kj6c:08488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc0dc45330]
[runnervm0kj6c:08488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc0dc9eb2c]
[runnervm0kj6c:08488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc0dc4527e]
[runnervm0kj6c:08488] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc0dc288ff]
[runnervm0kj6c:08488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc0e0a5ff5]
[runnervm0kj6c:08488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc0e0bb0da]
[runnervm0kj6c:08488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc0e0a5a55]
[runnervm0kj6c:08488] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc0e0a5a6f]
[runnervm0kj6c:08488] [ 8] plumed(+0x146dd)[0x56549b1cf6dd]
[runnervm0kj6c:08488] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc0dc2a1ca]
[runnervm0kj6c:08488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc0dc2a28b]
[runnervm0kj6c:08488] [11] plumed(+0x15365)[0x56549b1d0365]
[runnervm0kj6c:08488] *** End of error message ***
</pre>
{% endraw %}
