**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[pkrvmpptgkbjq6m:10557] *** Process received signal ***
[pkrvmpptgkbjq6m:10557] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10557] Signal code:  (-6)
[pkrvmpptgkbjq6m:10557] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1b2b445330]
[pkrvmpptgkbjq6m:10557] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1b2b49eb2c]
[pkrvmpptgkbjq6m:10557] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1b2b44527e]
[pkrvmpptgkbjq6m:10557] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1b2b4288ff]
[pkrvmpptgkbjq6m:10557] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1b2b8a5ff5]
[pkrvmpptgkbjq6m:10557] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1b2b8bb0da]
[pkrvmpptgkbjq6m:10557] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1b2b8a5a55]
[pkrvmpptgkbjq6m:10557] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1b2b8a5a6f]
[pkrvmpptgkbjq6m:10557] [ 8] plumed(+0x146dd)[0x5611f69326dd]
[pkrvmpptgkbjq6m:10557] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1b2b42a1ca]
[pkrvmpptgkbjq6m:10557] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1b2b42a28b]
[pkrvmpptgkbjq6m:10557] [11] plumed(+0x15365)[0x5611f6933365]
[pkrvmpptgkbjq6m:10557] *** End of error message ***
</pre>
{% endraw %}
