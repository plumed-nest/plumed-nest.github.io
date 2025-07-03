**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[pkrvmbietmlfzoi:11008] *** Process received signal ***
[pkrvmbietmlfzoi:11008] Signal: Aborted (6)
[pkrvmbietmlfzoi:11008] Signal code:  (-6)
[pkrvmbietmlfzoi:11008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a2fe45330]
[pkrvmbietmlfzoi:11008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a2fe9eb2c]
[pkrvmbietmlfzoi:11008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a2fe4527e]
[pkrvmbietmlfzoi:11008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a2fe288ff]
[pkrvmbietmlfzoi:11008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a302a5ff5]
[pkrvmbietmlfzoi:11008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a302bb0da]
[pkrvmbietmlfzoi:11008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a302a5a55]
[pkrvmbietmlfzoi:11008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a302a5a6f]
[pkrvmbietmlfzoi:11008] [ 8] plumed_master(+0x146dd)[0x55e0bcf156dd]
[pkrvmbietmlfzoi:11008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a2fe2a1ca]
[pkrvmbietmlfzoi:11008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a2fe2a28b]
[pkrvmbietmlfzoi:11008] [11] plumed_master(+0x15365)[0x55e0bcf16365]
[pkrvmbietmlfzoi:11008] *** End of error message ***
</pre>
{% endraw %}
