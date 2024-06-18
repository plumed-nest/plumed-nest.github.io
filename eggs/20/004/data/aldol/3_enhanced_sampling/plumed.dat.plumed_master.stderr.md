**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.31V3Cn.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.31V3Cn.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.31V3Cn.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.31V3Cn.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.31V3Cn.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1272-851:10127] *** Process received signal ***
[fv-az1272-851:10127] Signal: Aborted (6)
[fv-az1272-851:10127] Signal code:  (-6)
[fv-az1272-851:10127] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb1eb842520]
[fv-az1272-851:10127] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb1eb8969fc]
[fv-az1272-851:10127] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb1eb842476]
[fv-az1272-851:10127] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb1eb8287f3]
[fv-az1272-851:10127] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb1ebca2b9e]
[fv-az1272-851:10127] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb1ebcae20c]
[fv-az1272-851:10127] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb1ebcae277]
[fv-az1272-851:10127] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb1ebcae52b]
[fv-az1272-851:10127] [ 8] plumed_master(+0x14274)[0x55b1a32d9274]
[fv-az1272-851:10127] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb1eb829d90]
[fv-az1272-851:10127] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb1eb829e40]
[fv-az1272-851:10127] [11] plumed_master(+0x14ed5)[0x55b1a32d9ed5]
[fv-az1272-851:10127] *** End of error message ***
</pre>
{% endraw %}
