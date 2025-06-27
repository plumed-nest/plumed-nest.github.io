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
[pkrvmbietmlfzoi:66281] *** Process received signal ***
[pkrvmbietmlfzoi:66281] Signal: Aborted (6)
[pkrvmbietmlfzoi:66281] Signal code:  (-6)
[pkrvmbietmlfzoi:66281] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbdf9645330]
[pkrvmbietmlfzoi:66281] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbdf969eb2c]
[pkrvmbietmlfzoi:66281] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbdf964527e]
[pkrvmbietmlfzoi:66281] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbdf96288ff]
[pkrvmbietmlfzoi:66281] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbdf9aa5ff5]
[pkrvmbietmlfzoi:66281] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbdf9abb0da]
[pkrvmbietmlfzoi:66281] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbdf9aa5a55]
[pkrvmbietmlfzoi:66281] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbdf9aa5a6f]
[pkrvmbietmlfzoi:66281] [ 8] plumed_master(+0x146dd)[0x55a78d3b36dd]
[pkrvmbietmlfzoi:66281] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbdf962a1ca]
[pkrvmbietmlfzoi:66281] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbdf962a28b]
[pkrvmbietmlfzoi:66281] [11] plumed_master(+0x15365)[0x55a78d3b4365]
[pkrvmbietmlfzoi:66281] *** End of error message ***
</pre>
{% endraw %}
