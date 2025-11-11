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
[runnervmw9dnm:10821] *** Process received signal ***
[runnervmw9dnm:10821] Signal: Aborted (6)
[runnervmw9dnm:10821] Signal code:  (-6)
[runnervmw9dnm:10821] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1caea45330]
[runnervmw9dnm:10821] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1caea9eb2c]
[runnervmw9dnm:10821] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1caea4527e]
[runnervmw9dnm:10821] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1caea288ff]
[runnervmw9dnm:10821] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1caeea5ff5]
[runnervmw9dnm:10821] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1caeebb0da]
[runnervmw9dnm:10821] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1caeea5a55]
[runnervmw9dnm:10821] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1caeea5a6f]
[runnervmw9dnm:10821] [ 8] plumed_master(+0x146dd)[0x555ac280c6dd]
[runnervmw9dnm:10821] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1caea2a1ca]
[runnervmw9dnm:10821] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1caea2a28b]
[runnervmw9dnm:10821] [11] plumed_master(+0x15365)[0x555ac280d365]
[runnervmw9dnm:10821] *** End of error message ***
</pre>
{% endraw %}
