**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.UK57eH.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.UK57eH.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.UK57eH.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.UK57eH.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.UK57eH.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1771-923:07761] *** Process received signal ***
[fv-az1771-923:07761] Signal: Aborted (6)
[fv-az1771-923:07761] Signal code:  (-6)
[fv-az1771-923:07761] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe3f6c42520]
[fv-az1771-923:07761] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe3f6c969fc]
[fv-az1771-923:07761] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe3f6c42476]
[fv-az1771-923:07761] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe3f6c287f3]
[fv-az1771-923:07761] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe3f70a2b9e]
[fv-az1771-923:07761] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe3f70ae20c]
[fv-az1771-923:07761] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe3f70ae277]
[fv-az1771-923:07761] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe3f70ae52b]
[fv-az1771-923:07761] [ 8] plumed_master(+0x14274)[0x556dc4e5f274]
[fv-az1771-923:07761] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe3f6c29d90]
[fv-az1771-923:07761] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe3f6c29e40]
[fv-az1771-923:07761] [11] plumed_master(+0x14ed5)[0x556dc4e5fed5]
[fv-az1771-923:07761] *** End of error message ***
</pre>
{% endraw %}
