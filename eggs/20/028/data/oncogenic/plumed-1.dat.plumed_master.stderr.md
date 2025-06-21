**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:158) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[pkrvmxyh4eaekms:10947] *** Process received signal ***
[pkrvmxyh4eaekms:10947] Signal: Aborted (6)
[pkrvmxyh4eaekms:10947] Signal code:  (-6)
[pkrvmxyh4eaekms:10947] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f097c245330]
[pkrvmxyh4eaekms:10947] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f097c29eb2c]
[pkrvmxyh4eaekms:10947] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f097c24527e]
[pkrvmxyh4eaekms:10947] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f097c2288ff]
[pkrvmxyh4eaekms:10947] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f097c6a5ff5]
[pkrvmxyh4eaekms:10947] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f097c6bb0da]
[pkrvmxyh4eaekms:10947] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f097c6a5a55]
[pkrvmxyh4eaekms:10947] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f097c6a5a6f]
[pkrvmxyh4eaekms:10947] [ 8] plumed_master(+0x146dd)[0x5626dd8686dd]
[pkrvmxyh4eaekms:10947] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f097c22a1ca]
[pkrvmxyh4eaekms:10947] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f097c22a28b]
[pkrvmxyh4eaekms:10947] [11] plumed_master(+0x15365)[0x5626dd869365]
[pkrvmxyh4eaekms:10947] *** End of error message ***
</pre>
{% endraw %}
