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
[pkrvmbietmlfzoi:66418] *** Process received signal ***
[pkrvmbietmlfzoi:66418] Signal: Aborted (6)
[pkrvmbietmlfzoi:66418] Signal code:  (-6)
[pkrvmbietmlfzoi:66418] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4cca045330]
[pkrvmbietmlfzoi:66418] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4cca09eb2c]
[pkrvmbietmlfzoi:66418] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4cca04527e]
[pkrvmbietmlfzoi:66418] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4cca0288ff]
[pkrvmbietmlfzoi:66418] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4cca4a5ff5]
[pkrvmbietmlfzoi:66418] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4cca4bb0da]
[pkrvmbietmlfzoi:66418] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4cca4a5a55]
[pkrvmbietmlfzoi:66418] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4cca4a5a6f]
[pkrvmbietmlfzoi:66418] [ 8] plumed_master(+0x146dd)[0x55f75e9216dd]
[pkrvmbietmlfzoi:66418] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4cca02a1ca]
[pkrvmbietmlfzoi:66418] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4cca02a28b]
[pkrvmbietmlfzoi:66418] [11] plumed_master(+0x15365)[0x55f75e922365]
[pkrvmbietmlfzoi:66418] *** End of error message ***
</pre>
{% endraw %}
