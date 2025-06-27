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
[pkrvmbietmlfzoi:66265] *** Process received signal ***
[pkrvmbietmlfzoi:66265] Signal: Aborted (6)
[pkrvmbietmlfzoi:66265] Signal code:  (-6)
[pkrvmbietmlfzoi:66265] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe629045330]
[pkrvmbietmlfzoi:66265] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe62909eb2c]
[pkrvmbietmlfzoi:66265] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe62904527e]
[pkrvmbietmlfzoi:66265] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe6290288ff]
[pkrvmbietmlfzoi:66265] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe6294a5ff5]
[pkrvmbietmlfzoi:66265] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe6294bb0da]
[pkrvmbietmlfzoi:66265] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe6294a5a55]
[pkrvmbietmlfzoi:66265] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe6294a5a6f]
[pkrvmbietmlfzoi:66265] [ 8] plumed(+0x146dd)[0x5566241d16dd]
[pkrvmbietmlfzoi:66265] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe62902a1ca]
[pkrvmbietmlfzoi:66265] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe62902a28b]
[pkrvmbietmlfzoi:66265] [11] plumed(+0x15365)[0x5566241d2365]
[pkrvmbietmlfzoi:66265] *** End of error message ***
</pre>
{% endraw %}
