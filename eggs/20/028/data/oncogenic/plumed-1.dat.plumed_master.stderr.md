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
[runnervmvrwv9:11323] *** Process received signal ***
[runnervmvrwv9:11323] Signal: Aborted (6)
[runnervmvrwv9:11323] Signal code:  (-6)
[runnervmvrwv9:11323] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f52a7445330]
[runnervmvrwv9:11323] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f52a749eb2c]
[runnervmvrwv9:11323] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f52a744527e]
[runnervmvrwv9:11323] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f52a74288ff]
[runnervmvrwv9:11323] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f52a78a5ff5]
[runnervmvrwv9:11323] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f52a78bb0da]
[runnervmvrwv9:11323] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f52a78a5a55]
[runnervmvrwv9:11323] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f52a78a5a6f]
[runnervmvrwv9:11323] [ 8] plumed_master(+0x146dd)[0x558aa94376dd]
[runnervmvrwv9:11323] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f52a742a1ca]
[runnervmvrwv9:11323] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f52a742a28b]
[runnervmvrwv9:11323] [11] plumed_master(+0x15365)[0x558aa9438365]
[runnervmvrwv9:11323] *** End of error message ***
</pre>
{% endraw %}
