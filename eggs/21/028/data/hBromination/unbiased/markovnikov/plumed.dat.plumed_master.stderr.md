**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[pkrvmberfyhpb9w:11039] *** Process received signal ***
[pkrvmberfyhpb9w:11039] Signal: Aborted (6)
[pkrvmberfyhpb9w:11039] Signal code:  (-6)
[pkrvmberfyhpb9w:11039] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbed1645330]
[pkrvmberfyhpb9w:11039] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbed169eb2c]
[pkrvmberfyhpb9w:11039] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbed164527e]
[pkrvmberfyhpb9w:11039] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbed16288ff]
[pkrvmberfyhpb9w:11039] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbed1aa5ff5]
[pkrvmberfyhpb9w:11039] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbed1abb0da]
[pkrvmberfyhpb9w:11039] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbed1aa5a55]
[pkrvmberfyhpb9w:11039] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbed1aa5a6f]
[pkrvmberfyhpb9w:11039] [ 8] plumed_master(+0x146dd)[0x55a2784f46dd]
[pkrvmberfyhpb9w:11039] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbed162a1ca]
[pkrvmberfyhpb9w:11039] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbed162a28b]
[pkrvmberfyhpb9w:11039] [11] plumed_master(+0x15365)[0x55a2784f5365]
[pkrvmberfyhpb9w:11039] *** End of error message ***
</pre>
{% endraw %}
