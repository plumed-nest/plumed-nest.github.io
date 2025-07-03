**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:158) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[pkrvmbietmlfzoi:11523] *** Process received signal ***
[pkrvmbietmlfzoi:11523] Signal: Aborted (6)
[pkrvmbietmlfzoi:11523] Signal code:  (-6)
[pkrvmbietmlfzoi:11523] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f95ae645330]
[pkrvmbietmlfzoi:11523] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f95ae69eb2c]
[pkrvmbietmlfzoi:11523] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f95ae64527e]
[pkrvmbietmlfzoi:11523] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95ae6288ff]
[pkrvmbietmlfzoi:11523] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95aeaa5ff5]
[pkrvmbietmlfzoi:11523] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95aeabb0da]
[pkrvmbietmlfzoi:11523] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95aeaa5a55]
[pkrvmbietmlfzoi:11523] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95aeaa5a6f]
[pkrvmbietmlfzoi:11523] [ 8] plumed_master(+0x146dd)[0x55fc105666dd]
[pkrvmbietmlfzoi:11523] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f95ae62a1ca]
[pkrvmbietmlfzoi:11523] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f95ae62a28b]
[pkrvmbietmlfzoi:11523] [11] plumed_master(+0x15365)[0x55fc10567365]
[pkrvmbietmlfzoi:11523] *** End of error message ***
</pre>
{% endraw %}
