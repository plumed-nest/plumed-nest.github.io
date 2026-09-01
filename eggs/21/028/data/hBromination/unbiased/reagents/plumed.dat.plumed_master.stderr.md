**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[runnervmgx7h7:08830] *** Process received signal ***
[runnervmgx7h7:08830] Signal: Aborted (6)
[runnervmgx7h7:08830] Signal code:  (-6)
[runnervmgx7h7:08830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff65e245330]
[runnervmgx7h7:08830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff65e29ec0c]
[runnervmgx7h7:08830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff65e24527e]
[runnervmgx7h7:08830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff65e2288ff]
[runnervmgx7h7:08830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff65e6a5ff5]
[runnervmgx7h7:08830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff65e6bb0da]
[runnervmgx7h7:08830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff65e6a5a55]
[runnervmgx7h7:08830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff65e6a5a6f]
[runnervmgx7h7:08830] [ 8] plumed_master(+0x146dd)[0x55782666a6dd]
[runnervmgx7h7:08830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff65e22a1ca]
[runnervmgx7h7:08830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff65e22a28b]
[runnervmgx7h7:08830] [11] plumed_master(+0x15365)[0x55782666b365]
[runnervmgx7h7:08830] *** End of error message ***
</pre>
{% endraw %}
