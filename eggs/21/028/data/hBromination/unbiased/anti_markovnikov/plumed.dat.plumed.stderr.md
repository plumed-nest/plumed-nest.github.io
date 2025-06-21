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
[pkrvmxyh4eaekms:09286] *** Process received signal ***
[pkrvmxyh4eaekms:09286] Signal: Aborted (6)
[pkrvmxyh4eaekms:09286] Signal code:  (-6)
[pkrvmxyh4eaekms:09286] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8121e45330]
[pkrvmxyh4eaekms:09286] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8121e9eb2c]
[pkrvmxyh4eaekms:09286] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8121e4527e]
[pkrvmxyh4eaekms:09286] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8121e288ff]
[pkrvmxyh4eaekms:09286] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81222a5ff5]
[pkrvmxyh4eaekms:09286] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81222bb0da]
[pkrvmxyh4eaekms:09286] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81222a5a55]
[pkrvmxyh4eaekms:09286] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81222a5a6f]
[pkrvmxyh4eaekms:09286] [ 8] plumed(+0x146dd)[0x563fff2936dd]
[pkrvmxyh4eaekms:09286] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8121e2a1ca]
[pkrvmxyh4eaekms:09286] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8121e2a28b]
[pkrvmxyh4eaekms:09286] [11] plumed(+0x15365)[0x563fff294365]
[pkrvmxyh4eaekms:09286] *** End of error message ***
</pre>
{% endraw %}
