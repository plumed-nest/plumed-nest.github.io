**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.73HYhd.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.73HYhd.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.73HYhd.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.73HYhd.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.73HYhd.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmf6wy0o8zjz:65450] *** Process received signal ***
[pkrvmf6wy0o8zjz:65450] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65450] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65450] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb9ca45330]
[pkrvmf6wy0o8zjz:65450] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb9ca9eb2c]
[pkrvmf6wy0o8zjz:65450] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb9ca4527e]
[pkrvmf6wy0o8zjz:65450] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb9ca288ff]
[pkrvmf6wy0o8zjz:65450] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb9cea5ff5]
[pkrvmf6wy0o8zjz:65450] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb9cebb0da]
[pkrvmf6wy0o8zjz:65450] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb9cea5a55]
[pkrvmf6wy0o8zjz:65450] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb9cea5a6f]
[pkrvmf6wy0o8zjz:65450] [ 8] plumed(+0x146dd)[0x55f46c6206dd]
[pkrvmf6wy0o8zjz:65450] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb9ca2a1ca]
[pkrvmf6wy0o8zjz:65450] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb9ca2a28b]
[pkrvmf6wy0o8zjz:65450] [11] plumed(+0x15365)[0x55f46c621365]
[pkrvmf6wy0o8zjz:65450] *** End of error message ***
</pre>
{% endraw %}
