**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[pkrvmbietmlfzoi:10950] *** Process received signal ***
[pkrvmbietmlfzoi:10950] Signal: Aborted (6)
[pkrvmbietmlfzoi:10950] Signal code:  (-6)
[pkrvmbietmlfzoi:10950] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ce2a45330]
[pkrvmbietmlfzoi:10950] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ce2a9eb2c]
[pkrvmbietmlfzoi:10950] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ce2a4527e]
[pkrvmbietmlfzoi:10950] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ce2a288ff]
[pkrvmbietmlfzoi:10950] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ce2ea5ff5]
[pkrvmbietmlfzoi:10950] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ce2ebb0da]
[pkrvmbietmlfzoi:10950] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ce2ea5a55]
[pkrvmbietmlfzoi:10950] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ce2ea5a6f]
[pkrvmbietmlfzoi:10950] [ 8] plumed_master(+0x146dd)[0x5653af29d6dd]
[pkrvmbietmlfzoi:10950] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ce2a2a1ca]
[pkrvmbietmlfzoi:10950] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ce2a2a28b]
[pkrvmbietmlfzoi:10950] [11] plumed_master(+0x15365)[0x5653af29e365]
[pkrvmbietmlfzoi:10950] *** End of error message ***
</pre>
{% endraw %}
