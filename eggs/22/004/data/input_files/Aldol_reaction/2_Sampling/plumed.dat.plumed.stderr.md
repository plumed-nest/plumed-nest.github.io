**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
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
[fv-az1272-890:70182] *** Process received signal ***
[fv-az1272-890:70182] Signal: Aborted (6)
[fv-az1272-890:70182] Signal code:  (-6)
[fv-az1272-890:70182] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc922442520]
[fv-az1272-890:70182] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc9224969fc]
[fv-az1272-890:70182] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc922442476]
[fv-az1272-890:70182] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc9224287f3]
[fv-az1272-890:70182] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fc9228a4f26]
[fv-az1272-890:70182] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fc9228b6d9c]
[fv-az1272-890:70182] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fc9228b6e07]
[fv-az1272-890:70182] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc9228b70bb]
[fv-az1272-890:70182] [ 8] plumed(+0x12f48)[0x55e68140bf48]
[fv-az1272-890:70182] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc922429d90]
[fv-az1272-890:70182] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc922429e40]
[fv-az1272-890:70182] [11] plumed(+0x131e5)[0x55e68140c1e5]
[fv-az1272-890:70182] *** End of error message ***
</pre>
{% endraw %}
