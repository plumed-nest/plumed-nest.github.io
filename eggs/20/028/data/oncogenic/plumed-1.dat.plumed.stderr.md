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
[pkrvmpptgkbjq6m:12314] *** Process received signal ***
[pkrvmpptgkbjq6m:12314] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12314] Signal code:  (-6)
[pkrvmpptgkbjq6m:12314] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe678645330]
[pkrvmpptgkbjq6m:12314] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe67869eb2c]
[pkrvmpptgkbjq6m:12314] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe67864527e]
[pkrvmpptgkbjq6m:12314] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe6786288ff]
[pkrvmpptgkbjq6m:12314] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe678aa5ff5]
[pkrvmpptgkbjq6m:12314] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe678abb0da]
[pkrvmpptgkbjq6m:12314] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe678aa5a55]
[pkrvmpptgkbjq6m:12314] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe678aa5a6f]
[pkrvmpptgkbjq6m:12314] [ 8] plumed(+0x146dd)[0x560c562f16dd]
[pkrvmpptgkbjq6m:12314] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe67862a1ca]
[pkrvmpptgkbjq6m:12314] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe67862a28b]
[pkrvmpptgkbjq6m:12314] [11] plumed(+0x15365)[0x560c562f2365]
[pkrvmpptgkbjq6m:12314] *** End of error message ***
</pre>
{% endraw %}
