**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.TQ3Qfy.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.TQ3Qfy.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.TQ3Qfy.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.TQ3Qfy.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.TQ3Qfy.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az768-943:07696] *** Process received signal ***
[fv-az768-943:07696] Signal: Aborted (6)
[fv-az768-943:07696] Signal code:  (-6)
[fv-az768-943:07696] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe90fa42520]
[fv-az768-943:07696] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe90fa969fc]
[fv-az768-943:07696] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe90fa42476]
[fv-az768-943:07696] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe90fa287f3]
[fv-az768-943:07696] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe90fea2b9e]
[fv-az768-943:07696] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe90feae20c]
[fv-az768-943:07696] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe90feae277]
[fv-az768-943:07696] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe90feae52b]
[fv-az768-943:07696] [ 8] plumed_master(+0x14274)[0x563f99f5b274]
[fv-az768-943:07696] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe90fa29d90]
[fv-az768-943:07696] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe90fa29e40]
[fv-az768-943:07696] [11] plumed_master(+0x14ed5)[0x563f99f5bed5]
[fv-az768-943:07696] *** End of error message ***
</pre>
{% endraw %}
