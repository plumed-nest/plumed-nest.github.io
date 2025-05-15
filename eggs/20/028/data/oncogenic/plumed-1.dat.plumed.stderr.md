**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[pkrvmberfyhpb9w:12945] *** Process received signal ***
[pkrvmberfyhpb9w:12945] Signal: Aborted (6)
[pkrvmberfyhpb9w:12945] Signal code:  (-6)
[pkrvmberfyhpb9w:12945] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa69a645330]
[pkrvmberfyhpb9w:12945] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa69a69eb2c]
[pkrvmberfyhpb9w:12945] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa69a64527e]
[pkrvmberfyhpb9w:12945] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa69a6288ff]
[pkrvmberfyhpb9w:12945] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa69aaa5ff5]
[pkrvmberfyhpb9w:12945] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa69aabb0da]
[pkrvmberfyhpb9w:12945] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa69aaa5a55]
[pkrvmberfyhpb9w:12945] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa69aaa5a6f]
[pkrvmberfyhpb9w:12945] [ 8] plumed(+0x146dd)[0x55e6a0edd6dd]
[pkrvmberfyhpb9w:12945] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa69a62a1ca]
[pkrvmberfyhpb9w:12945] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa69a62a28b]
[pkrvmberfyhpb9w:12945] [11] plumed(+0x15365)[0x55e6a0ede365]
[pkrvmberfyhpb9w:12945] *** End of error message ***
</pre>
{% endraw %}
