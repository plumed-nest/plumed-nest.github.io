**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.SaaW0E.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.SaaW0E.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.SaaW0E.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.SaaW0E.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.SaaW0E.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az530-623:10040] *** Process received signal ***
[fv-az530-623:10040] Signal: Aborted (6)
[fv-az530-623:10040] Signal code:  (-6)
[fv-az530-623:10040] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fadcc842520]
[fv-az530-623:10040] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fadcc8969fc]
[fv-az530-623:10040] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fadcc842476]
[fv-az530-623:10040] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fadcc8287f3]
[fv-az530-623:10040] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fadccca2b9e]
[fv-az530-623:10040] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fadcccae20c]
[fv-az530-623:10040] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fadcccae277]
[fv-az530-623:10040] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fadcccae52b]
[fv-az530-623:10040] [ 8] plumed_master(+0x14274)[0x55a7f85ab274]
[fv-az530-623:10040] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fadcc829d90]
[fv-az530-623:10040] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fadcc829e40]
[fv-az530-623:10040] [11] plumed_master(+0x14ed5)[0x55a7f85abed5]
[fv-az530-623:10040] *** End of error message ***
</pre>
{% endraw %}
