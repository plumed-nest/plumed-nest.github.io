**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:385) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az1691-811:11200] *** Process received signal ***
[fv-az1691-811:11200] Signal: Aborted (6)
[fv-az1691-811:11200] Signal code:  (-6)
[fv-az1691-811:11200] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc826645330]
[fv-az1691-811:11200] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc82669eb2c]
[fv-az1691-811:11200] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc82664527e]
[fv-az1691-811:11200] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc8266288ff]
[fv-az1691-811:11200] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc826aa5ff5]
[fv-az1691-811:11200] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc826abb0da]
[fv-az1691-811:11200] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc826aa5a55]
[fv-az1691-811:11200] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc826aa5a6f]
[fv-az1691-811:11200] [ 8] plumed_master(+0x146dd)[0x564c12dd16dd]
[fv-az1691-811:11200] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc82662a1ca]
[fv-az1691-811:11200] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc82662a28b]
[fv-az1691-811:11200] [11] plumed_master(+0x15365)[0x564c12dd2365]
[fv-az1691-811:11200] *** End of error message ***
</pre>
{% endraw %}
