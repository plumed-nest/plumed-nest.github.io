**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[runnervmw9dnm:10935] *** Process received signal ***
[runnervmw9dnm:10935] Signal: Aborted (6)
[runnervmw9dnm:10935] Signal code:  (-6)
[runnervmw9dnm:10935] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efdc9845330]
[runnervmw9dnm:10935] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efdc989eb2c]
[runnervmw9dnm:10935] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efdc984527e]
[runnervmw9dnm:10935] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efdc98288ff]
[runnervmw9dnm:10935] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efdc9ca5ff5]
[runnervmw9dnm:10935] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efdc9cbb0da]
[runnervmw9dnm:10935] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efdc9ca5a55]
[runnervmw9dnm:10935] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efdc9ca5a6f]
[runnervmw9dnm:10935] [ 8] plumed_master(+0x146dd)[0x55df1cb096dd]
[runnervmw9dnm:10935] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efdc982a1ca]
[runnervmw9dnm:10935] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efdc982a28b]
[runnervmw9dnm:10935] [11] plumed_master(+0x15365)[0x55df1cb0a365]
[runnervmw9dnm:10935] *** End of error message ***
</pre>
{% endraw %}
