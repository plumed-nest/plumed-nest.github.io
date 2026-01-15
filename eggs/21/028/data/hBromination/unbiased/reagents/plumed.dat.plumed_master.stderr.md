**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[runnervmi13qx:35655] *** Process received signal ***
[runnervmi13qx:35655] Signal: Aborted (6)
[runnervmi13qx:35655] Signal code:  (-6)
[runnervmi13qx:35655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe824445330]
[runnervmi13qx:35655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe82449eb2c]
[runnervmi13qx:35655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe82444527e]
[runnervmi13qx:35655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8244288ff]
[runnervmi13qx:35655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8248a5ff5]
[runnervmi13qx:35655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8248bb0da]
[runnervmi13qx:35655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8248a5a55]
[runnervmi13qx:35655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8248a5a6f]
[runnervmi13qx:35655] [ 8] plumed_master(+0x146dd)[0x55dbebf6d6dd]
[runnervmi13qx:35655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe82442a1ca]
[runnervmi13qx:35655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe82442a28b]
[runnervmi13qx:35655] [11] plumed_master(+0x15365)[0x55dbebf6e365]
[runnervmi13qx:35655] *** End of error message ***
</pre>
{% endraw %}
