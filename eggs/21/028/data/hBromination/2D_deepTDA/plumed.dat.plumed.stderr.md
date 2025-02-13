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
[fv-az1657-925:09289] *** Process received signal ***
[fv-az1657-925:09289] Signal: Aborted (6)
[fv-az1657-925:09289] Signal code:  (-6)
[fv-az1657-925:09289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca19445330]
[fv-az1657-925:09289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca1949eb2c]
[fv-az1657-925:09289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca1944527e]
[fv-az1657-925:09289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca194288ff]
[fv-az1657-925:09289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca198a5ff5]
[fv-az1657-925:09289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca198bb0da]
[fv-az1657-925:09289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca198a5a55]
[fv-az1657-925:09289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca198a5a6f]
[fv-az1657-925:09289] [ 8] plumed(+0x146dd)[0x565540d156dd]
[fv-az1657-925:09289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca1942a1ca]
[fv-az1657-925:09289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca1942a28b]
[fv-az1657-925:09289] [11] plumed(+0x15365)[0x565540d16365]
[fv-az1657-925:09289] *** End of error message ***
</pre>
{% endraw %}
