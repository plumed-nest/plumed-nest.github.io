**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:10837] *** Process received signal ***
[pkrvmbietmlfzoi:10837] Signal: Aborted (6)
[pkrvmbietmlfzoi:10837] Signal code:  (-6)
[pkrvmbietmlfzoi:10837] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f26c2045330]
[pkrvmbietmlfzoi:10837] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f26c209eb2c]
[pkrvmbietmlfzoi:10837] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f26c204527e]
[pkrvmbietmlfzoi:10837] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f26c20288ff]
[pkrvmbietmlfzoi:10837] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f26c24a5ff5]
[pkrvmbietmlfzoi:10837] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f26c24bb0da]
[pkrvmbietmlfzoi:10837] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f26c24a5a55]
[pkrvmbietmlfzoi:10837] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f26c24a5a6f]
[pkrvmbietmlfzoi:10837] [ 8] plumed_master(+0x146dd)[0x55e5620046dd]
[pkrvmbietmlfzoi:10837] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f26c202a1ca]
[pkrvmbietmlfzoi:10837] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f26c202a28b]
[pkrvmbietmlfzoi:10837] [11] plumed_master(+0x15365)[0x55e562005365]
[pkrvmbietmlfzoi:10837] *** End of error message ***
</pre>
{% endraw %}
