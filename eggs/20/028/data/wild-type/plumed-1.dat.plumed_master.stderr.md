**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:172) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervmkj6or:08807] *** Process received signal ***
[runnervmkj6or:08807] Signal: Aborted (6)
[runnervmkj6or:08807] Signal code:  (-6)
[runnervmkj6or:08807] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff741e45330]
[runnervmkj6or:08807] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff741e9eb2c]
[runnervmkj6or:08807] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff741e4527e]
[runnervmkj6or:08807] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff741e288ff]
[runnervmkj6or:08807] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff7422a5ff5]
[runnervmkj6or:08807] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff7422bb0da]
[runnervmkj6or:08807] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff7422a5a55]
[runnervmkj6or:08807] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff7422a5a6f]
[runnervmkj6or:08807] [ 8] plumed_master(+0x146dd)[0x562b7523b6dd]
[runnervmkj6or:08807] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff741e2a1ca]
[runnervmkj6or:08807] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff741e2a28b]
[runnervmkj6or:08807] [11] plumed_master(+0x15365)[0x562b7523c365]
[runnervmkj6or:08807] *** End of error message ***
</pre>
{% endraw %}
