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
[fv-az805-507:09015] *** Process received signal ***
[fv-az805-507:09015] Signal: Aborted (6)
[fv-az805-507:09015] Signal code:  (-6)
[fv-az805-507:09015] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0694a45330]
[fv-az805-507:09015] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0694a9eb2c]
[fv-az805-507:09015] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0694a4527e]
[fv-az805-507:09015] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0694a288ff]
[fv-az805-507:09015] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0694ea5ff5]
[fv-az805-507:09015] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0694ebb0da]
[fv-az805-507:09015] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0694ea5a55]
[fv-az805-507:09015] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0694ea5a6f]
[fv-az805-507:09015] [ 8] plumed(+0x146dd)[0x556f45fc36dd]
[fv-az805-507:09015] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0694a2a1ca]
[fv-az805-507:09015] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0694a2a28b]
[fv-az805-507:09015] [11] plumed(+0x15365)[0x556f45fc4365]
[fv-az805-507:09015] *** End of error message ***
</pre>
{% endraw %}
