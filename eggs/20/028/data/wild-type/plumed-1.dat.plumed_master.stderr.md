**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:172) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervmw9dnm:11447] *** Process received signal ***
[runnervmw9dnm:11447] Signal: Aborted (6)
[runnervmw9dnm:11447] Signal code:  (-6)
[runnervmw9dnm:11447] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff967045330]
[runnervmw9dnm:11447] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff96709eb2c]
[runnervmw9dnm:11447] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff96704527e]
[runnervmw9dnm:11447] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff9670288ff]
[runnervmw9dnm:11447] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff9674a5ff5]
[runnervmw9dnm:11447] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff9674bb0da]
[runnervmw9dnm:11447] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff9674a5a55]
[runnervmw9dnm:11447] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff9674a5a6f]
[runnervmw9dnm:11447] [ 8] plumed_master(+0x146dd)[0x556a213ae6dd]
[runnervmw9dnm:11447] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff96702a1ca]
[runnervmw9dnm:11447] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff96702a28b]
[runnervmw9dnm:11447] [11] plumed_master(+0x15365)[0x556a213af365]
[runnervmw9dnm:11447] *** End of error message ***
</pre>
{% endraw %}
