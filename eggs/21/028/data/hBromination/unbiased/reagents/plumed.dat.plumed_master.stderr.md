**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[fv-az1771-923:07962] *** Process received signal ***
[fv-az1771-923:07962] Signal: Aborted (6)
[fv-az1771-923:07962] Signal code:  (-6)
[fv-az1771-923:07962] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5d2a842520]
[fv-az1771-923:07962] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5d2a8969fc]
[fv-az1771-923:07962] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5d2a842476]
[fv-az1771-923:07962] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5d2a8287f3]
[fv-az1771-923:07962] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5d2aca2b9e]
[fv-az1771-923:07962] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5d2acae20c]
[fv-az1771-923:07962] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5d2acae277]
[fv-az1771-923:07962] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5d2acae52b]
[fv-az1771-923:07962] [ 8] plumed_master(+0x14274)[0x55f1cca7a274]
[fv-az1771-923:07962] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5d2a829d90]
[fv-az1771-923:07962] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5d2a829e40]
[fv-az1771-923:07962] [11] plumed_master(+0x14ed5)[0x55f1cca7aed5]
[fv-az1771-923:07962] *** End of error message ***
</pre>
{% endraw %}
