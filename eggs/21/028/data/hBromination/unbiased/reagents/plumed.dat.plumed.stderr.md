**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmmklqx:07693] *** Process received signal ***
[runnervmmklqx:07693] Signal: Aborted (6)
[runnervmmklqx:07693] Signal code:  (-6)
[runnervmmklqx:07693] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe9ed245330]
[runnervmmklqx:07693] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe9ed29eb2c]
[runnervmmklqx:07693] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe9ed24527e]
[runnervmmklqx:07693] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9ed2288ff]
[runnervmmklqx:07693] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe9ed6a5ff5]
[runnervmmklqx:07693] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe9ed6bb0da]
[runnervmmklqx:07693] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe9ed6a5a55]
[runnervmmklqx:07693] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe9ed6a5a6f]
[runnervmmklqx:07693] [ 8] plumed(+0x146dd)[0x5645dd5656dd]
[runnervmmklqx:07693] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe9ed22a1ca]
[runnervmmklqx:07693] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe9ed22a28b]
[runnervmmklqx:07693] [11] plumed(+0x15365)[0x5645dd566365]
[runnervmmklqx:07693] *** End of error message ***
</pre>
{% endraw %}
