**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[runnervmi13qx:35599] *** Process received signal ***
[runnervmi13qx:35599] Signal: Aborted (6)
[runnervmi13qx:35599] Signal code:  (-6)
[runnervmi13qx:35599] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd41de45330]
[runnervmi13qx:35599] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd41de9eb2c]
[runnervmi13qx:35599] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd41de4527e]
[runnervmi13qx:35599] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd41de288ff]
[runnervmi13qx:35599] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd41e2a5ff5]
[runnervmi13qx:35599] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd41e2bb0da]
[runnervmi13qx:35599] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd41e2a5a55]
[runnervmi13qx:35599] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd41e2a5a6f]
[runnervmi13qx:35599] [ 8] plumed_master(+0x146dd)[0x55fd60fb66dd]
[runnervmi13qx:35599] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd41de2a1ca]
[runnervmi13qx:35599] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd41de2a28b]
[runnervmi13qx:35599] [11] plumed_master(+0x15365)[0x55fd60fb7365]
[runnervmi13qx:35599] *** End of error message ***
</pre>
{% endraw %}
