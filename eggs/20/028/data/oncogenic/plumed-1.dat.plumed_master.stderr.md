**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[fv-az805-507:09082] *** Process received signal ***
[fv-az805-507:09082] Signal: Aborted (6)
[fv-az805-507:09082] Signal code:  (-6)
[fv-az805-507:09082] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf79e45330]
[fv-az805-507:09082] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf79e9eb2c]
[fv-az805-507:09082] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf79e4527e]
[fv-az805-507:09082] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf79e288ff]
[fv-az805-507:09082] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf7a2a5ff5]
[fv-az805-507:09082] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf7a2bb0da]
[fv-az805-507:09082] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf7a2a5a55]
[fv-az805-507:09082] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf7a2a5a6f]
[fv-az805-507:09082] [ 8] plumed_master(+0x146dd)[0x561d3d97f6dd]
[fv-az805-507:09082] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf79e2a1ca]
[fv-az805-507:09082] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf79e2a28b]
[fv-az805-507:09082] [11] plumed_master(+0x15365)[0x561d3d980365]
[fv-az805-507:09082] *** End of error message ***
</pre>
{% endraw %}
