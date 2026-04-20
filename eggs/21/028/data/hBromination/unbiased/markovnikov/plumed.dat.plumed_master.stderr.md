**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[runnervmeorf1:10270] *** Process received signal ***
[runnervmeorf1:10270] Signal: Aborted (6)
[runnervmeorf1:10270] Signal code:  (-6)
[runnervmeorf1:10270] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa828e45330]
[runnervmeorf1:10270] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa828e9eb2c]
[runnervmeorf1:10270] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa828e4527e]
[runnervmeorf1:10270] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa828e288ff]
[runnervmeorf1:10270] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8292a5ff5]
[runnervmeorf1:10270] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8292bb0da]
[runnervmeorf1:10270] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8292a5a55]
[runnervmeorf1:10270] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8292a5a6f]
[runnervmeorf1:10270] [ 8] plumed_master(+0x146dd)[0x55e35d2776dd]
[runnervmeorf1:10270] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa828e2a1ca]
[runnervmeorf1:10270] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa828e2a28b]
[runnervmeorf1:10270] [11] plumed_master(+0x15365)[0x55e35d278365]
[runnervmeorf1:10270] *** End of error message ***
</pre>
{% endraw %}
