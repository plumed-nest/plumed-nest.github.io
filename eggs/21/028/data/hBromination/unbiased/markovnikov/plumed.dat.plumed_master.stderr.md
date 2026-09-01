**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[runnervmgx7h7:08778] *** Process received signal ***
[runnervmgx7h7:08778] Signal: Aborted (6)
[runnervmgx7h7:08778] Signal code:  (-6)
[runnervmgx7h7:08778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcebfc45330]
[runnervmgx7h7:08778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcebfc9ec0c]
[runnervmgx7h7:08778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcebfc4527e]
[runnervmgx7h7:08778] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcebfc288ff]
[runnervmgx7h7:08778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcec00a5ff5]
[runnervmgx7h7:08778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcec00bb0da]
[runnervmgx7h7:08778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcec00a5a55]
[runnervmgx7h7:08778] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcec00a5a6f]
[runnervmgx7h7:08778] [ 8] plumed_master(+0x146dd)[0x5600207066dd]
[runnervmgx7h7:08778] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcebfc2a1ca]
[runnervmgx7h7:08778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcebfc2a28b]
[runnervmgx7h7:08778] [11] plumed_master(+0x15365)[0x560020707365]
[runnervmgx7h7:08778] *** End of error message ***
</pre>
{% endraw %}
