**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[runnervmeorf1:10214] *** Process received signal ***
[runnervmeorf1:10214] Signal: Aborted (6)
[runnervmeorf1:10214] Signal code:  (-6)
[runnervmeorf1:10214] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f282b045330]
[runnervmeorf1:10214] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f282b09eb2c]
[runnervmeorf1:10214] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f282b04527e]
[runnervmeorf1:10214] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f282b0288ff]
[runnervmeorf1:10214] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f282b4a5ff5]
[runnervmeorf1:10214] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f282b4bb0da]
[runnervmeorf1:10214] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f282b4a5a55]
[runnervmeorf1:10214] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f282b4a5a6f]
[runnervmeorf1:10214] [ 8] plumed_master(+0x146dd)[0x56052d0066dd]
[runnervmeorf1:10214] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f282b02a1ca]
[runnervmeorf1:10214] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f282b02a28b]
[runnervmeorf1:10214] [11] plumed_master(+0x15365)[0x56052d007365]
[runnervmeorf1:10214] *** End of error message ***
</pre>
{% endraw %}
