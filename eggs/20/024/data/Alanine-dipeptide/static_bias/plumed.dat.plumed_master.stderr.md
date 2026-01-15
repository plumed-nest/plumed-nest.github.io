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
[runnervmi13qx:36486] *** Process received signal ***
[runnervmi13qx:36486] Signal: Aborted (6)
[runnervmi13qx:36486] Signal code:  (-6)
[runnervmi13qx:36486] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6778445330]
[runnervmi13qx:36486] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f677849eb2c]
[runnervmi13qx:36486] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f677844527e]
[runnervmi13qx:36486] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67784288ff]
[runnervmi13qx:36486] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67788a5ff5]
[runnervmi13qx:36486] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67788bb0da]
[runnervmi13qx:36486] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67788a5a55]
[runnervmi13qx:36486] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67788a5a6f]
[runnervmi13qx:36486] [ 8] plumed_master(+0x146dd)[0x5654f25ed6dd]
[runnervmi13qx:36486] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f677842a1ca]
[runnervmi13qx:36486] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f677842a28b]
[runnervmi13qx:36486] [11] plumed_master(+0x15365)[0x5654f25ee365]
[runnervmi13qx:36486] *** End of error message ***
</pre>
{% endraw %}
