**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.1eOkhk.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.1eOkhk.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.1eOkhk.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.1eOkhk.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.1eOkhk.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1108-992:71433] *** Process received signal ***
[fv-az1108-992:71433] Signal: Aborted (6)
[fv-az1108-992:71433] Signal code:  (-6)
[fv-az1108-992:71433] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7af9442520]
[fv-az1108-992:71433] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7af94969fc]
[fv-az1108-992:71433] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7af9442476]
[fv-az1108-992:71433] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7af94287f3]
[fv-az1108-992:71433] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f7af98a4f26]
[fv-az1108-992:71433] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f7af98b6d9c]
[fv-az1108-992:71433] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f7af98b6e07]
[fv-az1108-992:71433] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7af98b70bb]
[fv-az1108-992:71433] [ 8] plumed_master(+0x12e7f)[0x557425554e7f]
[fv-az1108-992:71433] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7af9429d90]
[fv-az1108-992:71433] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7af9429e40]
[fv-az1108-992:71433] [11] plumed_master(+0x13115)[0x557425555115]
[fv-az1108-992:71433] *** End of error message ***
</pre>
{% endraw %}
