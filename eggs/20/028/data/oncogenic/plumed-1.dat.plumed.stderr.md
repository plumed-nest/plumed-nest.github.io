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
[pkrvmxyh4eaekms:10932] *** Process received signal ***
[pkrvmxyh4eaekms:10932] Signal: Aborted (6)
[pkrvmxyh4eaekms:10932] Signal code:  (-6)
[pkrvmxyh4eaekms:10932] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f57c0e45330]
[pkrvmxyh4eaekms:10932] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f57c0e9eb2c]
[pkrvmxyh4eaekms:10932] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f57c0e4527e]
[pkrvmxyh4eaekms:10932] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f57c0e288ff]
[pkrvmxyh4eaekms:10932] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f57c12a5ff5]
[pkrvmxyh4eaekms:10932] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f57c12bb0da]
[pkrvmxyh4eaekms:10932] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f57c12a5a55]
[pkrvmxyh4eaekms:10932] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f57c12a5a6f]
[pkrvmxyh4eaekms:10932] [ 8] plumed(+0x146dd)[0x559f07a786dd]
[pkrvmxyh4eaekms:10932] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f57c0e2a1ca]
[pkrvmxyh4eaekms:10932] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f57c0e2a28b]
[pkrvmxyh4eaekms:10932] [11] plumed(+0x15365)[0x559f07a79365]
[pkrvmxyh4eaekms:10932] *** End of error message ***
</pre>
{% endraw %}
