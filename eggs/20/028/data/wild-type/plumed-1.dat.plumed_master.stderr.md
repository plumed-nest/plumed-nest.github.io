**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:173) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervmeorf1:10237] *** Process received signal ***
[runnervmeorf1:10237] Signal: Aborted (6)
[runnervmeorf1:10237] Signal code:  (-6)
[runnervmeorf1:10237] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff983a45330]
[runnervmeorf1:10237] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff983a9eb2c]
[runnervmeorf1:10237] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff983a4527e]
[runnervmeorf1:10237] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff983a288ff]
[runnervmeorf1:10237] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff983ea5ff5]
[runnervmeorf1:10237] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff983ebb0da]
[runnervmeorf1:10237] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff983ea5a55]
[runnervmeorf1:10237] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff983ea5a6f]
[runnervmeorf1:10237] [ 8] plumed_master(+0x146dd)[0x55864afdf6dd]
[runnervmeorf1:10237] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff983a2a1ca]
[runnervmeorf1:10237] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff983a2a28b]
[runnervmeorf1:10237] [11] plumed_master(+0x15365)[0x55864afe0365]
[runnervmeorf1:10237] *** End of error message ***
</pre>
{% endraw %}
