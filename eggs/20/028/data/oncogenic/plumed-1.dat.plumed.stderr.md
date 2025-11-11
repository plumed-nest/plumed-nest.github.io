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
[runnervmw9dnm:11483] *** Process received signal ***
[runnervmw9dnm:11483] Signal: Aborted (6)
[runnervmw9dnm:11483] Signal code:  (-6)
[runnervmw9dnm:11483] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc392c45330]
[runnervmw9dnm:11483] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc392c9eb2c]
[runnervmw9dnm:11483] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc392c4527e]
[runnervmw9dnm:11483] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc392c288ff]
[runnervmw9dnm:11483] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc3930a5ff5]
[runnervmw9dnm:11483] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc3930bb0da]
[runnervmw9dnm:11483] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc3930a5a55]
[runnervmw9dnm:11483] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc3930a5a6f]
[runnervmw9dnm:11483] [ 8] plumed(+0x146dd)[0x5592a19f86dd]
[runnervmw9dnm:11483] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc392c2a1ca]
[runnervmw9dnm:11483] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc392c2a28b]
[runnervmw9dnm:11483] [11] plumed(+0x15365)[0x5592a19f9365]
[runnervmw9dnm:11483] *** End of error message ***
</pre>
{% endraw %}
