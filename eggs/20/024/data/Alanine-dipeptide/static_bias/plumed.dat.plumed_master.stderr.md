**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[pkrvmbietmlfzoi:11801] *** Process received signal ***
[pkrvmbietmlfzoi:11801] Signal: Aborted (6)
[pkrvmbietmlfzoi:11801] Signal code:  (-6)
[pkrvmbietmlfzoi:11801] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1a7aa45330]
[pkrvmbietmlfzoi:11801] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1a7aa9eb2c]
[pkrvmbietmlfzoi:11801] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1a7aa4527e]
[pkrvmbietmlfzoi:11801] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1a7aa288ff]
[pkrvmbietmlfzoi:11801] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1a7aea5ff5]
[pkrvmbietmlfzoi:11801] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1a7aebb0da]
[pkrvmbietmlfzoi:11801] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1a7aea5a55]
[pkrvmbietmlfzoi:11801] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1a7aea5a6f]
[pkrvmbietmlfzoi:11801] [ 8] plumed_master(+0x146dd)[0x560874e006dd]
[pkrvmbietmlfzoi:11801] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1a7aa2a1ca]
[pkrvmbietmlfzoi:11801] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1a7aa2a28b]
[pkrvmbietmlfzoi:11801] [11] plumed_master(+0x15365)[0x560874e01365]
[pkrvmbietmlfzoi:11801] *** End of error message ***
</pre>
{% endraw %}
