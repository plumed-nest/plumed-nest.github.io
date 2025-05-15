**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmberfyhpb9w:10911] *** Process received signal ***
[pkrvmberfyhpb9w:10911] Signal: Aborted (6)
[pkrvmberfyhpb9w:10911] Signal code:  (-6)
[pkrvmberfyhpb9w:10911] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd21ac45330]
[pkrvmberfyhpb9w:10911] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd21ac9eb2c]
[pkrvmberfyhpb9w:10911] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd21ac4527e]
[pkrvmberfyhpb9w:10911] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd21ac288ff]
[pkrvmberfyhpb9w:10911] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd21b0a5ff5]
[pkrvmberfyhpb9w:10911] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd21b0bb0da]
[pkrvmberfyhpb9w:10911] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd21b0a5a55]
[pkrvmberfyhpb9w:10911] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd21b0a5a6f]
[pkrvmberfyhpb9w:10911] [ 8] plumed(+0x146dd)[0x5629a52ec6dd]
[pkrvmberfyhpb9w:10911] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd21ac2a1ca]
[pkrvmberfyhpb9w:10911] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd21ac2a28b]
[pkrvmberfyhpb9w:10911] [11] plumed(+0x15365)[0x5629a52ed365]
[pkrvmberfyhpb9w:10911] *** End of error message ***
</pre>
{% endraw %}
