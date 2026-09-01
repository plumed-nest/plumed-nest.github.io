**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
[runnervmgx7h7:08668] *** Process received signal ***
[runnervmgx7h7:08668] Signal: Aborted (6)
[runnervmgx7h7:08668] Signal code:  (-6)
[runnervmgx7h7:08668] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d40445330]
[runnervmgx7h7:08668] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d4049ec0c]
[runnervmgx7h7:08668] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d4044527e]
[runnervmgx7h7:08668] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d404288ff]
[runnervmgx7h7:08668] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d408a5ff5]
[runnervmgx7h7:08668] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d408bb0da]
[runnervmgx7h7:08668] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d408a5a55]
[runnervmgx7h7:08668] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d408a5a6f]
[runnervmgx7h7:08668] [ 8] plumed_master(+0x146dd)[0x555ac78b06dd]
[runnervmgx7h7:08668] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d4042a1ca]
[runnervmgx7h7:08668] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d4042a28b]
[runnervmgx7h7:08668] [11] plumed_master(+0x15365)[0x555ac78b1365]
[runnervmgx7h7:08668] *** End of error message ***
</pre>
{% endraw %}
