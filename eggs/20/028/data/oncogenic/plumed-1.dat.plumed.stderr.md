**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[pkrvmq0rgcvqdmg:10761] *** Process received signal ***
[pkrvmq0rgcvqdmg:10761] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:10761] Signal code:  (-6)
[pkrvmq0rgcvqdmg:10761] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f74a2845330]
[pkrvmq0rgcvqdmg:10761] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f74a289eb2c]
[pkrvmq0rgcvqdmg:10761] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f74a284527e]
[pkrvmq0rgcvqdmg:10761] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f74a28288ff]
[pkrvmq0rgcvqdmg:10761] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f74a2ca5ff5]
[pkrvmq0rgcvqdmg:10761] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f74a2cbb0da]
[pkrvmq0rgcvqdmg:10761] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f74a2ca5a55]
[pkrvmq0rgcvqdmg:10761] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f74a2ca5a6f]
[pkrvmq0rgcvqdmg:10761] [ 8] plumed(+0x146dd)[0x55bc0785d6dd]
[pkrvmq0rgcvqdmg:10761] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f74a282a1ca]
[pkrvmq0rgcvqdmg:10761] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f74a282a28b]
[pkrvmq0rgcvqdmg:10761] [11] plumed(+0x15365)[0x55bc0785e365]
[pkrvmq0rgcvqdmg:10761] *** End of error message ***
</pre>
{% endraw %}
