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
[pkrvmf6wy0o8zjz:67070] *** Process received signal ***
[pkrvmf6wy0o8zjz:67070] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:67070] Signal code:  (-6)
[pkrvmf6wy0o8zjz:67070] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd777445330]
[pkrvmf6wy0o8zjz:67070] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd77749eb2c]
[pkrvmf6wy0o8zjz:67070] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd77744527e]
[pkrvmf6wy0o8zjz:67070] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7774288ff]
[pkrvmf6wy0o8zjz:67070] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7778a5ff5]
[pkrvmf6wy0o8zjz:67070] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7778bb0da]
[pkrvmf6wy0o8zjz:67070] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7778a5a55]
[pkrvmf6wy0o8zjz:67070] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7778a5a6f]
[pkrvmf6wy0o8zjz:67070] [ 8] plumed(+0x146dd)[0x556fb55ea6dd]
[pkrvmf6wy0o8zjz:67070] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd77742a1ca]
[pkrvmf6wy0o8zjz:67070] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd77742a28b]
[pkrvmf6wy0o8zjz:67070] [11] plumed(+0x15365)[0x556fb55eb365]
[pkrvmf6wy0o8zjz:67070] *** End of error message ***
</pre>
{% endraw %}
