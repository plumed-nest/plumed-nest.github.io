**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Hydrobromination/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az1983-395:66215] *** Process received signal ***
[fv-az1983-395:66215] Signal: Aborted (6)
[fv-az1983-395:66215] Signal code:  (-6)
[fv-az1983-395:66215] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f32b8445330]
[fv-az1983-395:66215] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f32b849eb2c]
[fv-az1983-395:66215] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f32b844527e]
[fv-az1983-395:66215] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f32b84288ff]
[fv-az1983-395:66215] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32b88a5ff5]
[fv-az1983-395:66215] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32b88bb0da]
[fv-az1983-395:66215] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32b88a5a55]
[fv-az1983-395:66215] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32b88a5a6f]
[fv-az1983-395:66215] [ 8] plumed_master(+0x146dd)[0x56190e8c76dd]
[fv-az1983-395:66215] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f32b842a1ca]
[fv-az1983-395:66215] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f32b842a28b]
[fv-az1983-395:66215] [11] plumed_master(+0x15365)[0x56190e8c8365]
[fv-az1983-395:66215] *** End of error message ***
</pre>
{% endraw %}
