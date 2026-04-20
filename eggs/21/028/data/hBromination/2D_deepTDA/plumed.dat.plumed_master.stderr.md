**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmeorf1:10158] *** Process received signal ***
[runnervmeorf1:10158] Signal: Aborted (6)
[runnervmeorf1:10158] Signal code:  (-6)
[runnervmeorf1:10158] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7facd0c45330]
[runnervmeorf1:10158] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7facd0c9eb2c]
[runnervmeorf1:10158] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7facd0c4527e]
[runnervmeorf1:10158] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7facd0c288ff]
[runnervmeorf1:10158] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7facd10a5ff5]
[runnervmeorf1:10158] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7facd10bb0da]
[runnervmeorf1:10158] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7facd10a5a55]
[runnervmeorf1:10158] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7facd10a5a6f]
[runnervmeorf1:10158] [ 8] plumed_master(+0x146dd)[0x560b371bd6dd]
[runnervmeorf1:10158] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7facd0c2a1ca]
[runnervmeorf1:10158] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7facd0c2a28b]
[runnervmeorf1:10158] [11] plumed_master(+0x15365)[0x560b371be365]
[runnervmeorf1:10158] *** End of error message ***
</pre>
{% endraw %}
