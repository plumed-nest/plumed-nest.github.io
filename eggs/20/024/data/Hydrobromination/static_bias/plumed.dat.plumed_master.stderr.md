**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Hydrobromination/static_bias/plumed.dat   
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
[fv-az775-215:09383] *** Process received signal ***
[fv-az775-215:09383] Signal: Aborted (6)
[fv-az775-215:09383] Signal code:  (-6)
[fv-az775-215:09383] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f44ff442520]
[fv-az775-215:09383] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f44ff4969fc]
[fv-az775-215:09383] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f44ff442476]
[fv-az775-215:09383] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f44ff4287f3]
[fv-az775-215:09383] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f44ff8a2b9e]
[fv-az775-215:09383] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f44ff8ae20c]
[fv-az775-215:09383] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f44ff8ae277]
[fv-az775-215:09383] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f44ff8ae52b]
[fv-az775-215:09383] [ 8] plumed_master(+0x14254)[0x559de0235254]
[fv-az775-215:09383] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f44ff429d90]
[fv-az775-215:09383] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f44ff429e40]
[fv-az775-215:09383] [11] plumed_master(+0x14eb5)[0x559de0235eb5]
[fv-az775-215:09383] *** End of error message ***
</pre>
{% endraw %}
