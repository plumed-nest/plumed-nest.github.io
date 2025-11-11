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
[runnervmw9dnm:11432] *** Process received signal ***
[runnervmw9dnm:11432] Signal: Aborted (6)
[runnervmw9dnm:11432] Signal code:  (-6)
[runnervmw9dnm:11432] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efeae045330]
[runnervmw9dnm:11432] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efeae09eb2c]
[runnervmw9dnm:11432] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efeae04527e]
[runnervmw9dnm:11432] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efeae0288ff]
[runnervmw9dnm:11432] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efeae4a5ff5]
[runnervmw9dnm:11432] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efeae4bb0da]
[runnervmw9dnm:11432] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efeae4a5a55]
[runnervmw9dnm:11432] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efeae4a5a6f]
[runnervmw9dnm:11432] [ 8] plumed(+0x146dd)[0x55a7520e16dd]
[runnervmw9dnm:11432] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efeae02a1ca]
[runnervmw9dnm:11432] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efeae02a28b]
[runnervmw9dnm:11432] [11] plumed(+0x15365)[0x55a7520e2365]
[runnervmw9dnm:11432] *** End of error message ***
</pre>
{% endraw %}
