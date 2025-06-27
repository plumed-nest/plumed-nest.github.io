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
[pkrvmbietmlfzoi:67492] *** Process received signal ***
[pkrvmbietmlfzoi:67492] Signal: Aborted (6)
[pkrvmbietmlfzoi:67492] Signal code:  (-6)
[pkrvmbietmlfzoi:67492] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc9ff045330]
[pkrvmbietmlfzoi:67492] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc9ff09eb2c]
[pkrvmbietmlfzoi:67492] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc9ff04527e]
[pkrvmbietmlfzoi:67492] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9ff0288ff]
[pkrvmbietmlfzoi:67492] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9ff4a5ff5]
[pkrvmbietmlfzoi:67492] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9ff4bb0da]
[pkrvmbietmlfzoi:67492] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9ff4a5a55]
[pkrvmbietmlfzoi:67492] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9ff4a5a6f]
[pkrvmbietmlfzoi:67492] [ 8] plumed_master(+0x146dd)[0x55b2c12d96dd]
[pkrvmbietmlfzoi:67492] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc9ff02a1ca]
[pkrvmbietmlfzoi:67492] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc9ff02a28b]
[pkrvmbietmlfzoi:67492] [11] plumed_master(+0x15365)[0x55b2c12da365]
[pkrvmbietmlfzoi:67492] *** End of error message ***
</pre>
{% endraw %}
