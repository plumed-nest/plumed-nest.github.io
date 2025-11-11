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
[runnervmw9dnm:10878] *** Process received signal ***
[runnervmw9dnm:10878] Signal: Aborted (6)
[runnervmw9dnm:10878] Signal code:  (-6)
[runnervmw9dnm:10878] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe973245330]
[runnervmw9dnm:10878] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe97329eb2c]
[runnervmw9dnm:10878] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe97324527e]
[runnervmw9dnm:10878] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9732288ff]
[runnervmw9dnm:10878] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe9736a5ff5]
[runnervmw9dnm:10878] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe9736bb0da]
[runnervmw9dnm:10878] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe9736a5a55]
[runnervmw9dnm:10878] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe9736a5a6f]
[runnervmw9dnm:10878] [ 8] plumed_master(+0x146dd)[0x55f493e0f6dd]
[runnervmw9dnm:10878] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe97322a1ca]
[runnervmw9dnm:10878] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe97322a28b]
[runnervmw9dnm:10878] [11] plumed_master(+0x15365)[0x55f493e10365]
[runnervmw9dnm:10878] *** End of error message ***
</pre>
{% endraw %}
