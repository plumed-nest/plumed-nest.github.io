**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:210) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az530-623:10021] *** Process received signal ***
[fv-az530-623:10021] Signal: Aborted (6)
[fv-az530-623:10021] Signal code:  (-6)
[fv-az530-623:10021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fef10442520]
[fv-az530-623:10021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fef104969fc]
[fv-az530-623:10021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fef10442476]
[fv-az530-623:10021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fef104287f3]
[fv-az530-623:10021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fef108a2b9e]
[fv-az530-623:10021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fef108ae20c]
[fv-az530-623:10021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fef108ae277]
[fv-az530-623:10021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fef108ae52b]
[fv-az530-623:10021] [ 8] plumed(+0x12f48)[0x55920f3c5f48]
[fv-az530-623:10021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fef10429d90]
[fv-az530-623:10021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fef10429e40]
[fv-az530-623:10021] [11] plumed(+0x131e5)[0x55920f3c61e5]
[fv-az530-623:10021] *** End of error message ***
</pre>
{% endraw %}
