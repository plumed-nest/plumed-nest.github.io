**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[pkrvmberfyhpb9w:12892] *** Process received signal ***
[pkrvmberfyhpb9w:12892] Signal: Aborted (6)
[pkrvmberfyhpb9w:12892] Signal code:  (-6)
[pkrvmberfyhpb9w:12892] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa39e45330]
[pkrvmberfyhpb9w:12892] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa39e9eb2c]
[pkrvmberfyhpb9w:12892] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa39e4527e]
[pkrvmberfyhpb9w:12892] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa39e288ff]
[pkrvmberfyhpb9w:12892] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa3a2a5ff5]
[pkrvmberfyhpb9w:12892] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa3a2bb0da]
[pkrvmberfyhpb9w:12892] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa3a2a5a55]
[pkrvmberfyhpb9w:12892] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa3a2a5a6f]
[pkrvmberfyhpb9w:12892] [ 8] plumed(+0x146dd)[0x55bcba73d6dd]
[pkrvmberfyhpb9w:12892] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa39e2a1ca]
[pkrvmberfyhpb9w:12892] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa39e2a28b]
[pkrvmberfyhpb9w:12892] [11] plumed(+0x15365)[0x55bcba73e365]
[pkrvmberfyhpb9w:12892] *** End of error message ***
</pre>
{% endraw %}
