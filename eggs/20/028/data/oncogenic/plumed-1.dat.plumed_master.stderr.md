**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:173) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[runnervmmklqx:09743] *** Process received signal ***
[runnervmmklqx:09743] Signal: Aborted (6)
[runnervmmklqx:09743] Signal code:  (-6)
[runnervmmklqx:09743] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fefb2a45330]
[runnervmmklqx:09743] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fefb2a9eb2c]
[runnervmmklqx:09743] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fefb2a4527e]
[runnervmmklqx:09743] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fefb2a288ff]
[runnervmmklqx:09743] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fefb2ea5ff5]
[runnervmmklqx:09743] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fefb2ebb0da]
[runnervmmklqx:09743] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fefb2ea5a55]
[runnervmmklqx:09743] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fefb2ea5a6f]
[runnervmmklqx:09743] [ 8] plumed_master(+0x146dd)[0x555bbb98a6dd]
[runnervmmklqx:09743] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fefb2a2a1ca]
[runnervmmklqx:09743] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fefb2a2a28b]
[runnervmmklqx:09743] [11] plumed_master(+0x15365)[0x555bbb98b365]
[runnervmmklqx:09743] *** End of error message ***
</pre>
{% endraw %}
