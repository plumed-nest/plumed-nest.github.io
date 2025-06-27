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
[pkrvmbietmlfzoi:67529] *** Process received signal ***
[pkrvmbietmlfzoi:67529] Signal: Aborted (6)
[pkrvmbietmlfzoi:67529] Signal code:  (-6)
[pkrvmbietmlfzoi:67529] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcce0445330]
[pkrvmbietmlfzoi:67529] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcce049eb2c]
[pkrvmbietmlfzoi:67529] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcce044527e]
[pkrvmbietmlfzoi:67529] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcce04288ff]
[pkrvmbietmlfzoi:67529] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcce08a5ff5]
[pkrvmbietmlfzoi:67529] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcce08bb0da]
[pkrvmbietmlfzoi:67529] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcce08a5a55]
[pkrvmbietmlfzoi:67529] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcce08a5a6f]
[pkrvmbietmlfzoi:67529] [ 8] plumed(+0x146dd)[0x5654427106dd]
[pkrvmbietmlfzoi:67529] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcce042a1ca]
[pkrvmbietmlfzoi:67529] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcce042a28b]
[pkrvmbietmlfzoi:67529] [11] plumed(+0x15365)[0x565442711365]
[pkrvmbietmlfzoi:67529] *** End of error message ***
</pre>
{% endraw %}
