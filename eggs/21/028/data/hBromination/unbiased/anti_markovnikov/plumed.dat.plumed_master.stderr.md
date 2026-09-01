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
[runnervmgx7h7:08722] *** Process received signal ***
[runnervmgx7h7:08722] Signal: Aborted (6)
[runnervmgx7h7:08722] Signal code:  (-6)
[runnervmgx7h7:08722] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde45645330]
[runnervmgx7h7:08722] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde4569ec0c]
[runnervmgx7h7:08722] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde4564527e]
[runnervmgx7h7:08722] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde456288ff]
[runnervmgx7h7:08722] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde45aa5ff5]
[runnervmgx7h7:08722] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde45abb0da]
[runnervmgx7h7:08722] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde45aa5a55]
[runnervmgx7h7:08722] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde45aa5a6f]
[runnervmgx7h7:08722] [ 8] plumed_master(+0x146dd)[0x558c038296dd]
[runnervmgx7h7:08722] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde4562a1ca]
[runnervmgx7h7:08722] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde4562a28b]
[runnervmgx7h7:08722] [11] plumed_master(+0x15365)[0x558c0382a365]
[runnervmgx7h7:08722] *** End of error message ***
</pre>
{% endraw %}
