**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[pkrvmbietmlfzoi:10874] *** Process received signal ***
[pkrvmbietmlfzoi:10874] Signal: Aborted (6)
[pkrvmbietmlfzoi:10874] Signal code:  (-6)
[pkrvmbietmlfzoi:10874] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff7c5e45330]
[pkrvmbietmlfzoi:10874] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff7c5e9eb2c]
[pkrvmbietmlfzoi:10874] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff7c5e4527e]
[pkrvmbietmlfzoi:10874] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7c5e288ff]
[pkrvmbietmlfzoi:10874] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff7c62a5ff5]
[pkrvmbietmlfzoi:10874] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff7c62bb0da]
[pkrvmbietmlfzoi:10874] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff7c62a5a55]
[pkrvmbietmlfzoi:10874] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff7c62a5a6f]
[pkrvmbietmlfzoi:10874] [ 8] plumed(+0x146dd)[0x55cca2f156dd]
[pkrvmbietmlfzoi:10874] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff7c5e2a1ca]
[pkrvmbietmlfzoi:10874] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff7c5e2a28b]
[pkrvmbietmlfzoi:10874] [11] plumed(+0x15365)[0x55cca2f16365]
[pkrvmbietmlfzoi:10874] *** End of error message ***
</pre>
{% endraw %}
