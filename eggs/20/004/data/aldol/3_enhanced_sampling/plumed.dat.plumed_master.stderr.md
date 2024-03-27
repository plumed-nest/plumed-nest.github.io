**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.8XULc3.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.8XULc3.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.8XULc3.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.8XULc3.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.8XULc3.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1487-606:73501] *** Process received signal ***
[fv-az1487-606:73501] Signal: Aborted (6)
[fv-az1487-606:73501] Signal code:  (-6)
[fv-az1487-606:73501] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6fbb842520]
[fv-az1487-606:73501] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6fbb8969fc]
[fv-az1487-606:73501] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6fbb842476]
[fv-az1487-606:73501] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6fbb8287f3]
[fv-az1487-606:73501] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f6fbbca4f26]
[fv-az1487-606:73501] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f6fbbcb6d9c]
[fv-az1487-606:73501] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f6fbbcb6e07]
[fv-az1487-606:73501] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6fbbcb70bb]
[fv-az1487-606:73501] [ 8] plumed_master(+0x12e7f)[0x55dc980d4e7f]
[fv-az1487-606:73501] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6fbb829d90]
[fv-az1487-606:73501] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6fbb829e40]
[fv-az1487-606:73501] [11] plumed_master(+0x13115)[0x55dc980d5115]
[fv-az1487-606:73501] *** End of error message ***
</pre>
{% endraw %}
