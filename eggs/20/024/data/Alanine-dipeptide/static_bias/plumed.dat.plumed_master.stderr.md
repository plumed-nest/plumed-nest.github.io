**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
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
[fv-az1983-395:66131] *** Process received signal ***
[fv-az1983-395:66131] Signal: Aborted (6)
[fv-az1983-395:66131] Signal code:  (-6)
[fv-az1983-395:66131] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd0c8e45330]
[fv-az1983-395:66131] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd0c8e9eb2c]
[fv-az1983-395:66131] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd0c8e4527e]
[fv-az1983-395:66131] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd0c8e288ff]
[fv-az1983-395:66131] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd0c92a5ff5]
[fv-az1983-395:66131] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd0c92bb0da]
[fv-az1983-395:66131] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd0c92a5a55]
[fv-az1983-395:66131] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd0c92a5a6f]
[fv-az1983-395:66131] [ 8] plumed_master(+0x146dd)[0x5563c1fda6dd]
[fv-az1983-395:66131] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd0c8e2a1ca]
[fv-az1983-395:66131] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd0c8e2a28b]
[fv-az1983-395:66131] [11] plumed_master(+0x15365)[0x5563c1fdb365]
[fv-az1983-395:66131] *** End of error message ***
</pre>
{% endraw %}
