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
[pkrvmq0rgcvqdmg:09263] *** Process received signal ***
[pkrvmq0rgcvqdmg:09263] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09263] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09263] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fba3a845330]
[pkrvmq0rgcvqdmg:09263] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fba3a89eb2c]
[pkrvmq0rgcvqdmg:09263] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fba3a84527e]
[pkrvmq0rgcvqdmg:09263] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fba3a8288ff]
[pkrvmq0rgcvqdmg:09263] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fba3aca5ff5]
[pkrvmq0rgcvqdmg:09263] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fba3acbb0da]
[pkrvmq0rgcvqdmg:09263] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fba3aca5a55]
[pkrvmq0rgcvqdmg:09263] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fba3aca5a6f]
[pkrvmq0rgcvqdmg:09263] [ 8] plumed(+0x146dd)[0x563cb4f2f6dd]
[pkrvmq0rgcvqdmg:09263] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fba3a82a1ca]
[pkrvmq0rgcvqdmg:09263] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fba3a82a28b]
[pkrvmq0rgcvqdmg:09263] [11] plumed(+0x15365)[0x563cb4f30365]
[pkrvmq0rgcvqdmg:09263] *** End of error message ***
</pre>
{% endraw %}
