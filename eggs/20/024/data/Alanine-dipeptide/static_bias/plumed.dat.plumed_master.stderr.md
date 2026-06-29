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
[runnervmmklqx:10242] *** Process received signal ***
[runnervmmklqx:10242] Signal: Aborted (6)
[runnervmmklqx:10242] Signal code:  (-6)
[runnervmmklqx:10242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb88ee45330]
[runnervmmklqx:10242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb88ee9eb2c]
[runnervmmklqx:10242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb88ee4527e]
[runnervmmklqx:10242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb88ee288ff]
[runnervmmklqx:10242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb88f2a5ff5]
[runnervmmklqx:10242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb88f2bb0da]
[runnervmmklqx:10242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb88f2a5a55]
[runnervmmklqx:10242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb88f2a5a6f]
[runnervmmklqx:10242] [ 8] plumed_master(+0x146dd)[0x55cdcefa76dd]
[runnervmmklqx:10242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb88ee2a1ca]
[runnervmmklqx:10242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb88ee2a28b]
[runnervmmklqx:10242] [11] plumed_master(+0x15365)[0x55cdcefa8365]
[runnervmmklqx:10242] *** End of error message ***
</pre>
{% endraw %}
