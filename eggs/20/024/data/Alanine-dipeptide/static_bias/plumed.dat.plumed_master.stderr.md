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
[fv-az1719-476:11555] *** Process received signal ***
[fv-az1719-476:11555] Signal: Aborted (6)
[fv-az1719-476:11555] Signal code:  (-6)
[fv-az1719-476:11555] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc455e45330]
[fv-az1719-476:11555] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc455e9eb2c]
[fv-az1719-476:11555] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc455e4527e]
[fv-az1719-476:11555] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc455e288ff]
[fv-az1719-476:11555] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4562a5ff5]
[fv-az1719-476:11555] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4562bb0da]
[fv-az1719-476:11555] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4562a5a55]
[fv-az1719-476:11555] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4562a5a6f]
[fv-az1719-476:11555] [ 8] plumed_master(+0x146dd)[0x56162f6376dd]
[fv-az1719-476:11555] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc455e2a1ca]
[fv-az1719-476:11555] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc455e2a28b]
[fv-az1719-476:11555] [11] plumed_master(+0x15365)[0x56162f638365]
[fv-az1719-476:11555] *** End of error message ***
</pre>
{% endraw %}
