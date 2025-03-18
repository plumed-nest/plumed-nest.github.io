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
[fv-az1341-704:65426] *** Process received signal ***
[fv-az1341-704:65426] Signal: Aborted (6)
[fv-az1341-704:65426] Signal code:  (-6)
[fv-az1341-704:65426] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ab3e45330]
[fv-az1341-704:65426] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ab3e9eb2c]
[fv-az1341-704:65426] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ab3e4527e]
[fv-az1341-704:65426] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ab3e288ff]
[fv-az1341-704:65426] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ab42a5ff5]
[fv-az1341-704:65426] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ab42bb0da]
[fv-az1341-704:65426] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ab42a5a55]
[fv-az1341-704:65426] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ab42a5a6f]
[fv-az1341-704:65426] [ 8] plumed(+0x146dd)[0x55fbcc9c56dd]
[fv-az1341-704:65426] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ab3e2a1ca]
[fv-az1341-704:65426] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ab3e2a28b]
[fv-az1341-704:65426] [11] plumed(+0x15365)[0x55fbcc9c6365]
[fv-az1341-704:65426] *** End of error message ***
</pre>
{% endraw %}
