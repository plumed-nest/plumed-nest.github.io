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
[pkrvmq0rgcvqdmg:09318] *** Process received signal ***
[pkrvmq0rgcvqdmg:09318] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09318] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09318] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3c2a045330]
[pkrvmq0rgcvqdmg:09318] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3c2a09eb2c]
[pkrvmq0rgcvqdmg:09318] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3c2a04527e]
[pkrvmq0rgcvqdmg:09318] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3c2a0288ff]
[pkrvmq0rgcvqdmg:09318] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3c2a4a5ff5]
[pkrvmq0rgcvqdmg:09318] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3c2a4bb0da]
[pkrvmq0rgcvqdmg:09318] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3c2a4a5a55]
[pkrvmq0rgcvqdmg:09318] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3c2a4a5a6f]
[pkrvmq0rgcvqdmg:09318] [ 8] plumed(+0x146dd)[0x555f7afd06dd]
[pkrvmq0rgcvqdmg:09318] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3c2a02a1ca]
[pkrvmq0rgcvqdmg:09318] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3c2a02a28b]
[pkrvmq0rgcvqdmg:09318] [11] plumed(+0x15365)[0x555f7afd1365]
[pkrvmq0rgcvqdmg:09318] *** End of error message ***
</pre>
{% endraw %}
