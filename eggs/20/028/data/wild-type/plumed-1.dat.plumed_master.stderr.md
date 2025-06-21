**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:158) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[pkrvmxyh4eaekms:10892] *** Process received signal ***
[pkrvmxyh4eaekms:10892] Signal: Aborted (6)
[pkrvmxyh4eaekms:10892] Signal code:  (-6)
[pkrvmxyh4eaekms:10892] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d9f445330]
[pkrvmxyh4eaekms:10892] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d9f49eb2c]
[pkrvmxyh4eaekms:10892] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d9f44527e]
[pkrvmxyh4eaekms:10892] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d9f4288ff]
[pkrvmxyh4eaekms:10892] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d9f8a5ff5]
[pkrvmxyh4eaekms:10892] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d9f8bb0da]
[pkrvmxyh4eaekms:10892] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d9f8a5a55]
[pkrvmxyh4eaekms:10892] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d9f8a5a6f]
[pkrvmxyh4eaekms:10892] [ 8] plumed_master(+0x146dd)[0x55a7cc6e46dd]
[pkrvmxyh4eaekms:10892] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d9f42a1ca]
[pkrvmxyh4eaekms:10892] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d9f42a28b]
[pkrvmxyh4eaekms:10892] [11] plumed_master(+0x15365)[0x55a7cc6e5365]
[pkrvmxyh4eaekms:10892] *** End of error message ***
</pre>
{% endraw %}
