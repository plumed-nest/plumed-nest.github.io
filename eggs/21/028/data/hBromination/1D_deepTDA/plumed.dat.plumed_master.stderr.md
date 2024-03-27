**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.LQiQlg.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.LQiQlg.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.LQiQlg.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.LQiQlg.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.LQiQlg.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1108-992:71371] *** Process received signal ***
[fv-az1108-992:71371] Signal: Aborted (6)
[fv-az1108-992:71371] Signal code:  (-6)
[fv-az1108-992:71371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f06d6242520]
[fv-az1108-992:71371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f06d62969fc]
[fv-az1108-992:71371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f06d6242476]
[fv-az1108-992:71371] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f06d62287f3]
[fv-az1108-992:71371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f06d66a4f26]
[fv-az1108-992:71371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f06d66b6d9c]
[fv-az1108-992:71371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f06d66b6e07]
[fv-az1108-992:71371] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f06d66b70bb]
[fv-az1108-992:71371] [ 8] plumed_master(+0x12e7f)[0x55fe941c4e7f]
[fv-az1108-992:71371] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f06d6229d90]
[fv-az1108-992:71371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f06d6229e40]
[fv-az1108-992:71371] [11] plumed_master(+0x13115)[0x55fe941c5115]
[fv-az1108-992:71371] *** End of error message ***
</pre>
{% endraw %}
