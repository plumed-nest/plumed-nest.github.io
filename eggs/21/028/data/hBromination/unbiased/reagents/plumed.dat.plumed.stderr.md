**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[pkrvmbietmlfzoi:67639] *** Process received signal ***
[pkrvmbietmlfzoi:67639] Signal: Aborted (6)
[pkrvmbietmlfzoi:67639] Signal code:  (-6)
[pkrvmbietmlfzoi:67639] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4dec45330]
[pkrvmbietmlfzoi:67639] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4dec9eb2c]
[pkrvmbietmlfzoi:67639] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4dec4527e]
[pkrvmbietmlfzoi:67639] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4dec288ff]
[pkrvmbietmlfzoi:67639] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4df0a5ff5]
[pkrvmbietmlfzoi:67639] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4df0bb0da]
[pkrvmbietmlfzoi:67639] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4df0a5a55]
[pkrvmbietmlfzoi:67639] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4df0a5a6f]
[pkrvmbietmlfzoi:67639] [ 8] plumed(+0x146dd)[0x55707b0126dd]
[pkrvmbietmlfzoi:67639] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4dec2a1ca]
[pkrvmbietmlfzoi:67639] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4dec2a28b]
[pkrvmbietmlfzoi:67639] [11] plumed(+0x15365)[0x55707b013365]
[pkrvmbietmlfzoi:67639] *** End of error message ***
</pre>
{% endraw %}
