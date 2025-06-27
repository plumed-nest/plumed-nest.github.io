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
[pkrvmbietmlfzoi:67474] *** Process received signal ***
[pkrvmbietmlfzoi:67474] Signal: Aborted (6)
[pkrvmbietmlfzoi:67474] Signal code:  (-6)
[pkrvmbietmlfzoi:67474] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd424845330]
[pkrvmbietmlfzoi:67474] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd42489eb2c]
[pkrvmbietmlfzoi:67474] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd42484527e]
[pkrvmbietmlfzoi:67474] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4248288ff]
[pkrvmbietmlfzoi:67474] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd424ca5ff5]
[pkrvmbietmlfzoi:67474] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd424cbb0da]
[pkrvmbietmlfzoi:67474] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd424ca5a55]
[pkrvmbietmlfzoi:67474] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd424ca5a6f]
[pkrvmbietmlfzoi:67474] [ 8] plumed(+0x146dd)[0x55b3068566dd]
[pkrvmbietmlfzoi:67474] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd42482a1ca]
[pkrvmbietmlfzoi:67474] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd42482a28b]
[pkrvmbietmlfzoi:67474] [11] plumed(+0x15365)[0x55b306857365]
[pkrvmbietmlfzoi:67474] *** End of error message ***
</pre>
{% endraw %}
