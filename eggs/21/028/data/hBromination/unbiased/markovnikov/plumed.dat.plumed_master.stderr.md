**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:211) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1771-923:07915] *** Process received signal ***
[fv-az1771-923:07915] Signal: Aborted (6)
[fv-az1771-923:07915] Signal code:  (-6)
[fv-az1771-923:07915] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f27a2a42520]
[fv-az1771-923:07915] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f27a2a969fc]
[fv-az1771-923:07915] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f27a2a42476]
[fv-az1771-923:07915] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f27a2a287f3]
[fv-az1771-923:07915] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f27a2ea2b9e]
[fv-az1771-923:07915] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f27a2eae20c]
[fv-az1771-923:07915] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f27a2eae277]
[fv-az1771-923:07915] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f27a2eae52b]
[fv-az1771-923:07915] [ 8] plumed_master(+0x14274)[0x55f2edb7f274]
[fv-az1771-923:07915] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f27a2a29d90]
[fv-az1771-923:07915] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f27a2a29e40]
[fv-az1771-923:07915] [11] plumed_master(+0x14ed5)[0x55f2edb7fed5]
[fv-az1771-923:07915] *** End of error message ***
</pre>
{% endraw %}
