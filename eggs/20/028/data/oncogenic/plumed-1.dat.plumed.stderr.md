**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[runnervmmklqx:09727] *** Process received signal ***
[runnervmmklqx:09727] Signal: Aborted (6)
[runnervmmklqx:09727] Signal code:  (-6)
[runnervmmklqx:09727] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa08445330]
[runnervmmklqx:09727] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa0849eb2c]
[runnervmmklqx:09727] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa0844527e]
[runnervmmklqx:09727] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa084288ff]
[runnervmmklqx:09727] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa088a5ff5]
[runnervmmklqx:09727] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa088bb0da]
[runnervmmklqx:09727] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa088a5a55]
[runnervmmklqx:09727] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa088a5a6f]
[runnervmmklqx:09727] [ 8] plumed(+0x146dd)[0x55cfce6d96dd]
[runnervmmklqx:09727] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa0842a1ca]
[runnervmmklqx:09727] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa0842a28b]
[runnervmmklqx:09727] [11] plumed(+0x15365)[0x55cfce6da365]
[runnervmmklqx:09727] *** End of error message ***
</pre>
{% endraw %}
