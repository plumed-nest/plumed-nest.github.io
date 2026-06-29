**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:173) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervmmklqx:09692] *** Process received signal ***
[runnervmmklqx:09692] Signal: Aborted (6)
[runnervmmklqx:09692] Signal code:  (-6)
[runnervmmklqx:09692] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f116a245330]
[runnervmmklqx:09692] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f116a29eb2c]
[runnervmmklqx:09692] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f116a24527e]
[runnervmmklqx:09692] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f116a2288ff]
[runnervmmklqx:09692] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f116a6a5ff5]
[runnervmmklqx:09692] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f116a6bb0da]
[runnervmmklqx:09692] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f116a6a5a55]
[runnervmmklqx:09692] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f116a6a5a6f]
[runnervmmklqx:09692] [ 8] plumed_master(+0x146dd)[0x55c18f1eb6dd]
[runnervmmklqx:09692] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f116a22a1ca]
[runnervmmklqx:09692] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f116a22a28b]
[runnervmmklqx:09692] [11] plumed_master(+0x15365)[0x55c18f1ec365]
[runnervmmklqx:09692] *** End of error message ***
</pre>
{% endraw %}
