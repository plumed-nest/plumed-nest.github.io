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
[runnervmgx7h7:09000] *** Process received signal ***
[runnervmgx7h7:09000] Signal: Aborted (6)
[runnervmgx7h7:09000] Signal code:  (-6)
[runnervmgx7h7:09000] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b07c45330]
[runnervmgx7h7:09000] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b07c9ec0c]
[runnervmgx7h7:09000] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b07c4527e]
[runnervmgx7h7:09000] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b07c288ff]
[runnervmgx7h7:09000] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b080a5ff5]
[runnervmgx7h7:09000] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b080bb0da]
[runnervmgx7h7:09000] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b080a5a55]
[runnervmgx7h7:09000] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b080a5a6f]
[runnervmgx7h7:09000] [ 8] plumed_master(+0x146dd)[0x558605e7d6dd]
[runnervmgx7h7:09000] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b07c2a1ca]
[runnervmgx7h7:09000] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b07c2a28b]
[runnervmgx7h7:09000] [11] plumed_master(+0x15365)[0x558605e7e365]
[runnervmgx7h7:09000] *** End of error message ***
</pre>
{% endraw %}
