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
[fv-az805-507:09066] *** Process received signal ***
[fv-az805-507:09066] Signal: Aborted (6)
[fv-az805-507:09066] Signal code:  (-6)
[fv-az805-507:09066] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b0fc45330]
[fv-az805-507:09066] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b0fc9eb2c]
[fv-az805-507:09066] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b0fc4527e]
[fv-az805-507:09066] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b0fc288ff]
[fv-az805-507:09066] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b100a5ff5]
[fv-az805-507:09066] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b100bb0da]
[fv-az805-507:09066] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b100a5a55]
[fv-az805-507:09066] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b100a5a6f]
[fv-az805-507:09066] [ 8] plumed(+0x146dd)[0x5602bb33a6dd]
[fv-az805-507:09066] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b0fc2a1ca]
[fv-az805-507:09066] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b0fc2a28b]
[fv-az805-507:09066] [11] plumed(+0x15365)[0x5602bb33b365]
[fv-az805-507:09066] *** End of error message ***
</pre>
{% endraw %}
