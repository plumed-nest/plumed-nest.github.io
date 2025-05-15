**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[pkrvmberfyhpb9w:10984] *** Process received signal ***
[pkrvmberfyhpb9w:10984] Signal: Aborted (6)
[pkrvmberfyhpb9w:10984] Signal code:  (-6)
[pkrvmberfyhpb9w:10984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0862445330]
[pkrvmberfyhpb9w:10984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f086249eb2c]
[pkrvmberfyhpb9w:10984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f086244527e]
[pkrvmberfyhpb9w:10984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f08624288ff]
[pkrvmberfyhpb9w:10984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f08628a5ff5]
[pkrvmberfyhpb9w:10984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f08628bb0da]
[pkrvmberfyhpb9w:10984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f08628a5a55]
[pkrvmberfyhpb9w:10984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f08628a5a6f]
[pkrvmberfyhpb9w:10984] [ 8] plumed_master(+0x146dd)[0x55ac910886dd]
[pkrvmberfyhpb9w:10984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f086242a1ca]
[pkrvmberfyhpb9w:10984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f086242a28b]
[pkrvmberfyhpb9w:10984] [11] plumed_master(+0x15365)[0x55ac91089365]
[pkrvmberfyhpb9w:10984] *** End of error message ***
</pre>
{% endraw %}
