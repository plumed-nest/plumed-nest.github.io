**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../Contacts.Zgh8AX.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../../Contacts.Zgh8AX.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../../Contacts.Zgh8AX.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../../Contacts.Zgh8AX.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../../Contacts.Zgh8AX.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1108-992:71621] *** Process received signal ***
[fv-az1108-992:71621] Signal: Aborted (6)
[fv-az1108-992:71621] Signal code:  (-6)
[fv-az1108-992:71621] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7db4242520]
[fv-az1108-992:71621] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7db42969fc]
[fv-az1108-992:71621] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7db4242476]
[fv-az1108-992:71621] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7db42287f3]
[fv-az1108-992:71621] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f7db46a4f26]
[fv-az1108-992:71621] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f7db46b6d9c]
[fv-az1108-992:71621] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f7db46b6e07]
[fv-az1108-992:71621] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7db46b70bb]
[fv-az1108-992:71621] [ 8] plumed_master(+0x12e7f)[0x55a6a86cde7f]
[fv-az1108-992:71621] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7db4229d90]
[fv-az1108-992:71621] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7db4229e40]
[fv-az1108-992:71621] [11] plumed_master(+0x13115)[0x55a6a86ce115]
[fv-az1108-992:71621] *** End of error message ***
</pre>
{% endraw %}
