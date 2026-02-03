**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervmkj6or:08791] *** Process received signal ***
[runnervmkj6or:08791] Signal: Aborted (6)
[runnervmkj6or:08791] Signal code:  (-6)
[runnervmkj6or:08791] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2bdc45330]
[runnervmkj6or:08791] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2bdc9eb2c]
[runnervmkj6or:08791] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2bdc4527e]
[runnervmkj6or:08791] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2bdc288ff]
[runnervmkj6or:08791] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2be0a5ff5]
[runnervmkj6or:08791] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2be0bb0da]
[runnervmkj6or:08791] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2be0a5a55]
[runnervmkj6or:08791] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2be0a5a6f]
[runnervmkj6or:08791] [ 8] plumed(+0x146dd)[0x55e430ee96dd]
[runnervmkj6or:08791] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2bdc2a1ca]
[runnervmkj6or:08791] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2bdc2a28b]
[runnervmkj6or:08791] [11] plumed(+0x15365)[0x55e430eea365]
[runnervmkj6or:08791] *** End of error message ***
</pre>
{% endraw %}
