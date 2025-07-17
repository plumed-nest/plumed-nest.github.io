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
[pkrvmq0rgcvqdmg:09429] *** Process received signal ***
[pkrvmq0rgcvqdmg:09429] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09429] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09429] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efdeda45330]
[pkrvmq0rgcvqdmg:09429] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efdeda9eb2c]
[pkrvmq0rgcvqdmg:09429] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efdeda4527e]
[pkrvmq0rgcvqdmg:09429] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efdeda288ff]
[pkrvmq0rgcvqdmg:09429] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efdedea5ff5]
[pkrvmq0rgcvqdmg:09429] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efdedebb0da]
[pkrvmq0rgcvqdmg:09429] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efdedea5a55]
[pkrvmq0rgcvqdmg:09429] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efdedea5a6f]
[pkrvmq0rgcvqdmg:09429] [ 8] plumed(+0x146dd)[0x55b94cc6e6dd]
[pkrvmq0rgcvqdmg:09429] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efdeda2a1ca]
[pkrvmq0rgcvqdmg:09429] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efdeda2a28b]
[pkrvmq0rgcvqdmg:09429] [11] plumed(+0x15365)[0x55b94cc6f365]
[pkrvmq0rgcvqdmg:09429] *** End of error message ***
</pre>
{% endraw %}
