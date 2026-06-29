**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervmmklqx:09676] *** Process received signal ***
[runnervmmklqx:09676] Signal: Aborted (6)
[runnervmmklqx:09676] Signal code:  (-6)
[runnervmmklqx:09676] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0fb6445330]
[runnervmmklqx:09676] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0fb649eb2c]
[runnervmmklqx:09676] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0fb644527e]
[runnervmmklqx:09676] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0fb64288ff]
[runnervmmklqx:09676] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0fb68a5ff5]
[runnervmmklqx:09676] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0fb68bb0da]
[runnervmmklqx:09676] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0fb68a5a55]
[runnervmmklqx:09676] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0fb68a5a6f]
[runnervmmklqx:09676] [ 8] plumed(+0x146dd)[0x55aae46b96dd]
[runnervmmklqx:09676] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0fb642a1ca]
[runnervmmklqx:09676] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0fb642a28b]
[runnervmmklqx:09676] [11] plumed(+0x15365)[0x55aae46ba365]
[runnervmmklqx:09676] *** End of error message ***
</pre>
{% endraw %}
