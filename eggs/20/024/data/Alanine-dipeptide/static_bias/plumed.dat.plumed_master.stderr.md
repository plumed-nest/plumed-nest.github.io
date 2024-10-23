**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:168) void PLMD::Keywords::use(const string&)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az775-215:09314] *** Process received signal ***
[fv-az775-215:09314] Signal: Aborted (6)
[fv-az775-215:09314] Signal code:  (-6)
[fv-az775-215:09314] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2e6e642520]
[fv-az775-215:09314] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2e6e6969fc]
[fv-az775-215:09314] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2e6e642476]
[fv-az775-215:09314] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2e6e6287f3]
[fv-az775-215:09314] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2e6eaa2b9e]
[fv-az775-215:09314] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2e6eaae20c]
[fv-az775-215:09314] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2e6eaae277]
[fv-az775-215:09314] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2e6eaae52b]
[fv-az775-215:09314] [ 8] plumed_master(+0x14254)[0x555d22fb6254]
[fv-az775-215:09314] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2e6e629d90]
[fv-az775-215:09314] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2e6e629e40]
[fv-az775-215:09314] [11] plumed_master(+0x14eb5)[0x555d22fb6eb5]
[fv-az775-215:09314] *** End of error message ***
</pre>
{% endraw %}
