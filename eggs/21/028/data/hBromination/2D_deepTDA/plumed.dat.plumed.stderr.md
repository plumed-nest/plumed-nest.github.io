**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:10819] *** Process received signal ***
[pkrvmbietmlfzoi:10819] Signal: Aborted (6)
[pkrvmbietmlfzoi:10819] Signal code:  (-6)
[pkrvmbietmlfzoi:10819] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5397845330]
[pkrvmbietmlfzoi:10819] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f539789eb2c]
[pkrvmbietmlfzoi:10819] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f539784527e]
[pkrvmbietmlfzoi:10819] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53978288ff]
[pkrvmbietmlfzoi:10819] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5397ca5ff5]
[pkrvmbietmlfzoi:10819] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5397cbb0da]
[pkrvmbietmlfzoi:10819] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5397ca5a55]
[pkrvmbietmlfzoi:10819] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5397ca5a6f]
[pkrvmbietmlfzoi:10819] [ 8] plumed(+0x146dd)[0x55a7df7606dd]
[pkrvmbietmlfzoi:10819] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f539782a1ca]
[pkrvmbietmlfzoi:10819] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f539782a28b]
[pkrvmbietmlfzoi:10819] [11] plumed(+0x15365)[0x55a7df761365]
[pkrvmbietmlfzoi:10819] *** End of error message ***
</pre>
{% endraw %}
