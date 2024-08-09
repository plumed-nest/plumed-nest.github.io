**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.pfvNHZ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.pfvNHZ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.pfvNHZ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.pfvNHZ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.pfvNHZ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1490-855:06799] *** Process received signal ***
[fv-az1490-855:06799] Signal: Aborted (6)
[fv-az1490-855:06799] Signal code:  (-6)
[fv-az1490-855:06799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc56fe42520]
[fv-az1490-855:06799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc56fe969fc]
[fv-az1490-855:06799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc56fe42476]
[fv-az1490-855:06799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc56fe287f3]
[fv-az1490-855:06799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc5702a2b9e]
[fv-az1490-855:06799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc5702ae20c]
[fv-az1490-855:06799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc5702ae277]
[fv-az1490-855:06799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc5702ae52b]
[fv-az1490-855:06799] [ 8] plumed_master(+0x14274)[0x559796c95274]
[fv-az1490-855:06799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc56fe29d90]
[fv-az1490-855:06799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc56fe29e40]
[fv-az1490-855:06799] [11] plumed_master(+0x14ed5)[0x559796c95ed5]
[fv-az1490-855:06799] *** End of error message ***
</pre>
{% endraw %}
