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
[pkrvmbietmlfzoi:66230] *** Process received signal ***
[pkrvmbietmlfzoi:66230] Signal: Aborted (6)
[pkrvmbietmlfzoi:66230] Signal code:  (-6)
[pkrvmbietmlfzoi:66230] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed21a45330]
[pkrvmbietmlfzoi:66230] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed21a9eb2c]
[pkrvmbietmlfzoi:66230] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed21a4527e]
[pkrvmbietmlfzoi:66230] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed21a288ff]
[pkrvmbietmlfzoi:66230] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed21ea5ff5]
[pkrvmbietmlfzoi:66230] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed21ebb0da]
[pkrvmbietmlfzoi:66230] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed21ea5a55]
[pkrvmbietmlfzoi:66230] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed21ea5a6f]
[pkrvmbietmlfzoi:66230] [ 8] plumed_master(+0x146dd)[0x560eb7bbc6dd]
[pkrvmbietmlfzoi:66230] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed21a2a1ca]
[pkrvmbietmlfzoi:66230] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed21a2a28b]
[pkrvmbietmlfzoi:66230] [11] plumed_master(+0x15365)[0x560eb7bbd365]
[pkrvmbietmlfzoi:66230] *** End of error message ***
</pre>
{% endraw %}
