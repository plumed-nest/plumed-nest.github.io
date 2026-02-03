**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervmkj6or:09808] *** Process received signal ***
[runnervmkj6or:09808] Signal: Aborted (6)
[runnervmkj6or:09808] Signal code:  (-6)
[runnervmkj6or:09808] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3747e45330]
[runnervmkj6or:09808] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3747e9eb2c]
[runnervmkj6or:09808] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3747e4527e]
[runnervmkj6or:09808] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3747e288ff]
[runnervmkj6or:09808] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37482a5ff5]
[runnervmkj6or:09808] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37482bb0da]
[runnervmkj6or:09808] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37482a5a55]
[runnervmkj6or:09808] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37482a5a6f]
[runnervmkj6or:09808] [ 8] plumed_master(+0x146dd)[0x5650d195b6dd]
[runnervmkj6or:09808] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3747e2a1ca]
[runnervmkj6or:09808] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3747e2a28b]
[runnervmkj6or:09808] [11] plumed_master(+0x15365)[0x5650d195c365]
[runnervmkj6or:09808] *** End of error message ***
</pre>
{% endraw %}
