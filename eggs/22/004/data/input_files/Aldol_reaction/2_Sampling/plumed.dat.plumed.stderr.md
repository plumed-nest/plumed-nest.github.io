**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.dRiWXE.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.dRiWXE.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.dRiWXE.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.dRiWXE.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.dRiWXE.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1429-284:05579] *** Process received signal ***
[fv-az1429-284:05579] Signal: Aborted (6)
[fv-az1429-284:05579] Signal code:  (-6)
[fv-az1429-284:05579] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f18a4042520]
[fv-az1429-284:05579] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f18a40969fc]
[fv-az1429-284:05579] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f18a4042476]
[fv-az1429-284:05579] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f18a40287f3]
[fv-az1429-284:05579] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f18a44a2b9e]
[fv-az1429-284:05579] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f18a44ae20c]
[fv-az1429-284:05579] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f18a44ae277]
[fv-az1429-284:05579] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f18a44ae52b]
[fv-az1429-284:05579] [ 8] plumed(+0x14254)[0x5561bc663254]
[fv-az1429-284:05579] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f18a4029d90]
[fv-az1429-284:05579] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f18a4029e40]
[fv-az1429-284:05579] [11] plumed(+0x14eb5)[0x5561bc663eb5]
[fv-az1429-284:05579] *** End of error message ***
</pre>
{% endraw %}
