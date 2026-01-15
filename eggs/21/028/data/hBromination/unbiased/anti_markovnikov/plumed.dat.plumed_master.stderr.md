**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmi13qx:35544] *** Process received signal ***
[runnervmi13qx:35544] Signal: Aborted (6)
[runnervmi13qx:35544] Signal code:  (-6)
[runnervmi13qx:35544] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f81645330]
[runnervmi13qx:35544] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f8169eb2c]
[runnervmi13qx:35544] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f8164527e]
[runnervmi13qx:35544] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f816288ff]
[runnervmi13qx:35544] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f81aa5ff5]
[runnervmi13qx:35544] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f81abb0da]
[runnervmi13qx:35544] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f81aa5a55]
[runnervmi13qx:35544] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f81aa5a6f]
[runnervmi13qx:35544] [ 8] plumed_master(+0x146dd)[0x55667633b6dd]
[runnervmi13qx:35544] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f8162a1ca]
[runnervmi13qx:35544] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f8162a28b]
[runnervmi13qx:35544] [11] plumed_master(+0x15365)[0x55667633c365]
[runnervmi13qx:35544] *** End of error message ***
</pre>
{% endraw %}
