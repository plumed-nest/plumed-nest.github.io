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
[pkrvmq0rgcvqdmg:09374] *** Process received signal ***
[pkrvmq0rgcvqdmg:09374] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09374] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09374] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0cb3845330]
[pkrvmq0rgcvqdmg:09374] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0cb389eb2c]
[pkrvmq0rgcvqdmg:09374] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0cb384527e]
[pkrvmq0rgcvqdmg:09374] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0cb38288ff]
[pkrvmq0rgcvqdmg:09374] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0cb3ca5ff5]
[pkrvmq0rgcvqdmg:09374] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0cb3cbb0da]
[pkrvmq0rgcvqdmg:09374] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0cb3ca5a55]
[pkrvmq0rgcvqdmg:09374] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0cb3ca5a6f]
[pkrvmq0rgcvqdmg:09374] [ 8] plumed(+0x146dd)[0x5589e36b66dd]
[pkrvmq0rgcvqdmg:09374] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0cb382a1ca]
[pkrvmq0rgcvqdmg:09374] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0cb382a28b]
[pkrvmq0rgcvqdmg:09374] [11] plumed(+0x15365)[0x5589e36b7365]
[pkrvmq0rgcvqdmg:09374] *** End of error message ***
</pre>
{% endraw %}
