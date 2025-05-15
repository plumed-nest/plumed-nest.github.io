**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[pkrvmberfyhpb9w:12908] *** Process received signal ***
[pkrvmberfyhpb9w:12908] Signal: Aborted (6)
[pkrvmberfyhpb9w:12908] Signal code:  (-6)
[pkrvmberfyhpb9w:12908] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf7f845330]
[pkrvmberfyhpb9w:12908] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf7f89eb2c]
[pkrvmberfyhpb9w:12908] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf7f84527e]
[pkrvmberfyhpb9w:12908] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf7f8288ff]
[pkrvmberfyhpb9w:12908] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf7fca5ff5]
[pkrvmberfyhpb9w:12908] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf7fcbb0da]
[pkrvmberfyhpb9w:12908] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf7fca5a55]
[pkrvmberfyhpb9w:12908] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf7fca5a6f]
[pkrvmberfyhpb9w:12908] [ 8] plumed_master(+0x146dd)[0x55c20cee86dd]
[pkrvmberfyhpb9w:12908] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf7f82a1ca]
[pkrvmberfyhpb9w:12908] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf7f82a28b]
[pkrvmberfyhpb9w:12908] [11] plumed_master(+0x15365)[0x55c20cee9365]
[pkrvmberfyhpb9w:12908] *** End of error message ***
</pre>
{% endraw %}
