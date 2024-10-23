**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Hydrobromination/known_propene/plumed.dat   
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
[fv-az775-215:09349] *** Process received signal ***
[fv-az775-215:09349] Signal: Aborted (6)
[fv-az775-215:09349] Signal code:  (-6)
[fv-az775-215:09349] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb2d0842520]
[fv-az775-215:09349] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb2d08969fc]
[fv-az775-215:09349] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb2d0842476]
[fv-az775-215:09349] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb2d08287f3]
[fv-az775-215:09349] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb2d0ca2b9e]
[fv-az775-215:09349] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb2d0cae20c]
[fv-az775-215:09349] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb2d0cae277]
[fv-az775-215:09349] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb2d0cae52b]
[fv-az775-215:09349] [ 8] plumed_master(+0x14254)[0x5578bc372254]
[fv-az775-215:09349] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb2d0829d90]
[fv-az775-215:09349] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb2d0829e40]
[fv-az775-215:09349] [11] plumed_master(+0x14eb5)[0x5578bc372eb5]
[fv-az775-215:09349] *** End of error message ***
</pre>
{% endraw %}
