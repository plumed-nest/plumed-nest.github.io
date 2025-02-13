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
[fv-az1280-696:12573] *** Process received signal ***
[fv-az1280-696:12573] Signal: Aborted (6)
[fv-az1280-696:12573] Signal code:  (-6)
[fv-az1280-696:12573] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb99da45330]
[fv-az1280-696:12573] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb99da9eb2c]
[fv-az1280-696:12573] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb99da4527e]
[fv-az1280-696:12573] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb99da288ff]
[fv-az1280-696:12573] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb99dea5ff5]
[fv-az1280-696:12573] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb99debb0da]
[fv-az1280-696:12573] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb99dea5a55]
[fv-az1280-696:12573] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb99dea5a6f]
[fv-az1280-696:12573] [ 8] plumed_master(+0x146dd)[0x5574265496dd]
[fv-az1280-696:12573] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb99da2a1ca]
[fv-az1280-696:12573] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb99da2a28b]
[fv-az1280-696:12573] [11] plumed_master(+0x15365)[0x55742654a365]
[fv-az1280-696:12573] *** End of error message ***
</pre>
{% endraw %}
