**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmvrwv9:10481] *** Process received signal ***
[runnervmvrwv9:10481] Signal: Aborted (6)
[runnervmvrwv9:10481] Signal code:  (-6)
[runnervmvrwv9:10481] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8702645330]
[runnervmvrwv9:10481] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f870269eb2c]
[runnervmvrwv9:10481] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f870264527e]
[runnervmvrwv9:10481] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f87026288ff]
[runnervmvrwv9:10481] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8702aa5ff5]
[runnervmvrwv9:10481] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8702abb0da]
[runnervmvrwv9:10481] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8702aa5a55]
[runnervmvrwv9:10481] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8702aa5a6f]
[runnervmvrwv9:10481] [ 8] plumed_master(+0x146dd)[0x556ae2e356dd]
[runnervmvrwv9:10481] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f870262a1ca]
[runnervmvrwv9:10481] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f870262a28b]
[runnervmvrwv9:10481] [11] plumed_master(+0x15365)[0x556ae2e36365]
[runnervmvrwv9:10481] *** End of error message ***
</pre>
{% endraw %}
