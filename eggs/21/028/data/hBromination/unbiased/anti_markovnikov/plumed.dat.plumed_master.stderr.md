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
[runnervmmklqx:07601] *** Process received signal ***
[runnervmmklqx:07601] Signal: Aborted (6)
[runnervmmklqx:07601] Signal code:  (-6)
[runnervmmklqx:07601] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4bf9845330]
[runnervmmklqx:07601] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4bf989eb2c]
[runnervmmklqx:07601] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4bf984527e]
[runnervmmklqx:07601] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4bf98288ff]
[runnervmmklqx:07601] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4bf9ca5ff5]
[runnervmmklqx:07601] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4bf9cbb0da]
[runnervmmklqx:07601] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4bf9ca5a55]
[runnervmmklqx:07601] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4bf9ca5a6f]
[runnervmmklqx:07601] [ 8] plumed_master(+0x146dd)[0x55fa440486dd]
[runnervmmklqx:07601] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4bf982a1ca]
[runnervmmklqx:07601] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4bf982a28b]
[runnervmmklqx:07601] [11] plumed_master(+0x15365)[0x55fa44049365]
[runnervmmklqx:07601] *** End of error message ***
</pre>
{% endraw %}
