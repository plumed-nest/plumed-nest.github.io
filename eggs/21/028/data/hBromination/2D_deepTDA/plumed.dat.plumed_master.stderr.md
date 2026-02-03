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
[runnervmkj6or:11086] *** Process received signal ***
[runnervmkj6or:11086] Signal: Aborted (6)
[runnervmkj6or:11086] Signal code:  (-6)
[runnervmkj6or:11086] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff500245330]
[runnervmkj6or:11086] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff50029eb2c]
[runnervmkj6or:11086] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff50024527e]
[runnervmkj6or:11086] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5002288ff]
[runnervmkj6or:11086] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5006a5ff5]
[runnervmkj6or:11086] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5006bb0da]
[runnervmkj6or:11086] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5006a5a55]
[runnervmkj6or:11086] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5006a5a6f]
[runnervmkj6or:11086] [ 8] plumed_master(+0x146dd)[0x55ee179ea6dd]
[runnervmkj6or:11086] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff50022a1ca]
[runnervmkj6or:11086] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff50022a28b]
[runnervmkj6or:11086] [11] plumed_master(+0x15365)[0x55ee179eb365]
[runnervmkj6or:11086] *** End of error message ***
</pre>
{% endraw %}
