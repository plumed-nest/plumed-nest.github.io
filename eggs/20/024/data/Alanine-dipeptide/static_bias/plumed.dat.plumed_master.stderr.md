**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervm76f27:08329] *** Process received signal ***
[runnervm76f27:08329] Signal: Aborted (6)
[runnervm76f27:08329] Signal code:  (-6)
[runnervm76f27:08329] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0d59e45330]
[runnervm76f27:08329] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0d59e9ec0c]
[runnervm76f27:08329] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0d59e4527e]
[runnervm76f27:08329] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0d59e288ff]
[runnervm76f27:08329] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0d5a2a5ff5]
[runnervm76f27:08329] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0d5a2bb0da]
[runnervm76f27:08329] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0d5a2a5a55]
[runnervm76f27:08329] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0d5a2a5a6f]
[runnervm76f27:08329] [ 8] plumed_master(+0x146dd)[0x55fe0aa9c6dd]
[runnervm76f27:08329] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0d59e2a1ca]
[runnervm76f27:08329] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0d59e2a28b]
[runnervm76f27:08329] [11] plumed_master(+0x15365)[0x55fe0aa9d365]
[runnervm76f27:08329] *** End of error message ***
</pre>
{% endraw %}
