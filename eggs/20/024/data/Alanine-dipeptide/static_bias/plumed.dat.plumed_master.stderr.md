**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[pkrvmberfyhpb9w:10857] *** Process received signal ***
[pkrvmberfyhpb9w:10857] Signal: Aborted (6)
[pkrvmberfyhpb9w:10857] Signal code:  (-6)
[pkrvmberfyhpb9w:10857] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc5a045330]
[pkrvmberfyhpb9w:10857] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc5a09eb2c]
[pkrvmberfyhpb9w:10857] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc5a04527e]
[pkrvmberfyhpb9w:10857] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc5a0288ff]
[pkrvmberfyhpb9w:10857] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc5a4a5ff5]
[pkrvmberfyhpb9w:10857] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc5a4bb0da]
[pkrvmberfyhpb9w:10857] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc5a4a5a55]
[pkrvmberfyhpb9w:10857] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc5a4a5a6f]
[pkrvmberfyhpb9w:10857] [ 8] plumed_master(+0x146dd)[0x559b5dd5f6dd]
[pkrvmberfyhpb9w:10857] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc5a02a1ca]
[pkrvmberfyhpb9w:10857] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc5a02a28b]
[pkrvmberfyhpb9w:10857] [11] plumed_master(+0x15365)[0x559b5dd60365]
[pkrvmberfyhpb9w:10857] *** End of error message ***
</pre>
{% endraw %}
