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
[runnervmeorf1:10272] *** Process received signal ***
[runnervmeorf1:10272] Signal: Aborted (6)
[runnervmeorf1:10272] Signal code:  (-6)
[runnervmeorf1:10272] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ae2e45330]
[runnervmeorf1:10272] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ae2e9eb2c]
[runnervmeorf1:10272] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ae2e4527e]
[runnervmeorf1:10272] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ae2e288ff]
[runnervmeorf1:10272] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ae32a5ff5]
[runnervmeorf1:10272] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ae32bb0da]
[runnervmeorf1:10272] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ae32a5a55]
[runnervmeorf1:10272] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ae32a5a6f]
[runnervmeorf1:10272] [ 8] plumed(+0x146dd)[0x564680c376dd]
[runnervmeorf1:10272] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ae2e2a1ca]
[runnervmeorf1:10272] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ae2e2a28b]
[runnervmeorf1:10272] [11] plumed(+0x15365)[0x564680c38365]
[runnervmeorf1:10272] *** End of error message ***
</pre>
{% endraw %}
