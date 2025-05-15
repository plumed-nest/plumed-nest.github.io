**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:461) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmberfyhpb9w:10929] *** Process received signal ***
[pkrvmberfyhpb9w:10929] Signal: Aborted (6)
[pkrvmberfyhpb9w:10929] Signal code:  (-6)
[pkrvmberfyhpb9w:10929] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb6d0845330]
[pkrvmberfyhpb9w:10929] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb6d089eb2c]
[pkrvmberfyhpb9w:10929] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb6d084527e]
[pkrvmberfyhpb9w:10929] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb6d08288ff]
[pkrvmberfyhpb9w:10929] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6d0ca5ff5]
[pkrvmberfyhpb9w:10929] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6d0cbb0da]
[pkrvmberfyhpb9w:10929] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6d0ca5a55]
[pkrvmberfyhpb9w:10929] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6d0ca5a6f]
[pkrvmberfyhpb9w:10929] [ 8] plumed_master(+0x146dd)[0x5576d8c116dd]
[pkrvmberfyhpb9w:10929] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb6d082a1ca]
[pkrvmberfyhpb9w:10929] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb6d082a28b]
[pkrvmberfyhpb9w:10929] [11] plumed_master(+0x15365)[0x5576d8c12365]
[pkrvmberfyhpb9w:10929] *** End of error message ***
</pre>
{% endraw %}
