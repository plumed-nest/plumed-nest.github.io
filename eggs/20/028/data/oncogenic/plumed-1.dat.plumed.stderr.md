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
[runnervmi13qx:36985] *** Process received signal ***
[runnervmi13qx:36985] Signal: Aborted (6)
[runnervmi13qx:36985] Signal code:  (-6)
[runnervmi13qx:36985] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8888445330]
[runnervmi13qx:36985] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f888849eb2c]
[runnervmi13qx:36985] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f888844527e]
[runnervmi13qx:36985] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88884288ff]
[runnervmi13qx:36985] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88888a5ff5]
[runnervmi13qx:36985] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88888bb0da]
[runnervmi13qx:36985] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88888a5a55]
[runnervmi13qx:36985] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88888a5a6f]
[runnervmi13qx:36985] [ 8] plumed(+0x146dd)[0x562ba97936dd]
[runnervmi13qx:36985] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f888842a1ca]
[runnervmi13qx:36985] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f888842a28b]
[runnervmi13qx:36985] [11] plumed(+0x15365)[0x562ba9794365]
[runnervmi13qx:36985] *** End of error message ***
</pre>
{% endraw %}
