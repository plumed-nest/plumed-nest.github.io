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
[pkrvmbietmlfzoi:11457] *** Process received signal ***
[pkrvmbietmlfzoi:11457] Signal: Aborted (6)
[pkrvmbietmlfzoi:11457] Signal code:  (-6)
[pkrvmbietmlfzoi:11457] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f98a0645330]
[pkrvmbietmlfzoi:11457] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f98a069eb2c]
[pkrvmbietmlfzoi:11457] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f98a064527e]
[pkrvmbietmlfzoi:11457] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98a06288ff]
[pkrvmbietmlfzoi:11457] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98a0aa5ff5]
[pkrvmbietmlfzoi:11457] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98a0abb0da]
[pkrvmbietmlfzoi:11457] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98a0aa5a55]
[pkrvmbietmlfzoi:11457] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98a0aa5a6f]
[pkrvmbietmlfzoi:11457] [ 8] plumed(+0x146dd)[0x55845a5766dd]
[pkrvmbietmlfzoi:11457] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f98a062a1ca]
[pkrvmbietmlfzoi:11457] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f98a062a28b]
[pkrvmbietmlfzoi:11457] [11] plumed(+0x15365)[0x55845a577365]
[pkrvmbietmlfzoi:11457] *** End of error message ***
</pre>
{% endraw %}
