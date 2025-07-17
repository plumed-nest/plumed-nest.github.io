**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:158) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[pkrvmq0rgcvqdmg:10777] *** Process received signal ***
[pkrvmq0rgcvqdmg:10777] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:10777] Signal code:  (-6)
[pkrvmq0rgcvqdmg:10777] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f84ec445330]
[pkrvmq0rgcvqdmg:10777] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f84ec49eb2c]
[pkrvmq0rgcvqdmg:10777] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f84ec44527e]
[pkrvmq0rgcvqdmg:10777] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f84ec4288ff]
[pkrvmq0rgcvqdmg:10777] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84ec8a5ff5]
[pkrvmq0rgcvqdmg:10777] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84ec8bb0da]
[pkrvmq0rgcvqdmg:10777] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84ec8a5a55]
[pkrvmq0rgcvqdmg:10777] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84ec8a5a6f]
[pkrvmq0rgcvqdmg:10777] [ 8] plumed_master(+0x146dd)[0x560eda2956dd]
[pkrvmq0rgcvqdmg:10777] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f84ec42a1ca]
[pkrvmq0rgcvqdmg:10777] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f84ec42a28b]
[pkrvmq0rgcvqdmg:10777] [11] plumed_master(+0x15365)[0x560eda296365]
[pkrvmq0rgcvqdmg:10777] *** End of error message ***
</pre>
{% endraw %}
