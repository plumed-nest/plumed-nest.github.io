**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:158) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[pkrvmbietmlfzoi:11472] *** Process received signal ***
[pkrvmbietmlfzoi:11472] Signal: Aborted (6)
[pkrvmbietmlfzoi:11472] Signal code:  (-6)
[pkrvmbietmlfzoi:11472] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3fe5445330]
[pkrvmbietmlfzoi:11472] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3fe549eb2c]
[pkrvmbietmlfzoi:11472] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3fe544527e]
[pkrvmbietmlfzoi:11472] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3fe54288ff]
[pkrvmbietmlfzoi:11472] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3fe58a5ff5]
[pkrvmbietmlfzoi:11472] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3fe58bb0da]
[pkrvmbietmlfzoi:11472] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3fe58a5a55]
[pkrvmbietmlfzoi:11472] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3fe58a5a6f]
[pkrvmbietmlfzoi:11472] [ 8] plumed_master(+0x146dd)[0x56015ee646dd]
[pkrvmbietmlfzoi:11472] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3fe542a1ca]
[pkrvmbietmlfzoi:11472] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3fe542a28b]
[pkrvmbietmlfzoi:11472] [11] plumed_master(+0x15365)[0x56015ee65365]
[pkrvmbietmlfzoi:11472] *** End of error message ***
</pre>
{% endraw %}
