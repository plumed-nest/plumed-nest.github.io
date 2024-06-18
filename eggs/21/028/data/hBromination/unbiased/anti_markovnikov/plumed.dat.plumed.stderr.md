**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../Contacts.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../../Contacts.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../../Contacts.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../../Contacts.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../../Contacts.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:210) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1771-923:07852] *** Process received signal ***
[fv-az1771-923:07852] Signal: Aborted (6)
[fv-az1771-923:07852] Signal code:  (-6)
[fv-az1771-923:07852] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc8acc42520]
[fv-az1771-923:07852] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc8acc969fc]
[fv-az1771-923:07852] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc8acc42476]
[fv-az1771-923:07852] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc8acc287f3]
[fv-az1771-923:07852] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc8ad0a2b9e]
[fv-az1771-923:07852] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc8ad0ae20c]
[fv-az1771-923:07852] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc8ad0ae277]
[fv-az1771-923:07852] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc8ad0ae52b]
[fv-az1771-923:07852] [ 8] plumed(+0x12f48)[0x562efcb8af48]
[fv-az1771-923:07852] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc8acc29d90]
[fv-az1771-923:07852] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc8acc29e40]
[fv-az1771-923:07852] [11] plumed(+0x131e5)[0x562efcb8b1e5]
[fv-az1771-923:07852] *** End of error message ***
</pre>
{% endraw %}
