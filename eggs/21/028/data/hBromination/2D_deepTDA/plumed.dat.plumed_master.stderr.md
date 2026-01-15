**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
[runnervmi13qx:35487] *** Process received signal ***
[runnervmi13qx:35487] Signal: Aborted (6)
[runnervmi13qx:35487] Signal code:  (-6)
[runnervmi13qx:35487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcda9c45330]
[runnervmi13qx:35487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcda9c9eb2c]
[runnervmi13qx:35487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcda9c4527e]
[runnervmi13qx:35487] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcda9c288ff]
[runnervmi13qx:35487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcdaa0a5ff5]
[runnervmi13qx:35487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcdaa0bb0da]
[runnervmi13qx:35487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcdaa0a5a55]
[runnervmi13qx:35487] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcdaa0a5a6f]
[runnervmi13qx:35487] [ 8] plumed_master(+0x146dd)[0x560cdf94e6dd]
[runnervmi13qx:35487] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcda9c2a1ca]
[runnervmi13qx:35487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcda9c2a28b]
[runnervmi13qx:35487] [11] plumed_master(+0x15365)[0x560cdf94f365]
[runnervmi13qx:35487] *** End of error message ***
</pre>
{% endraw %}
