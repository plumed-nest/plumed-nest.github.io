**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmw9dnm:10861] *** Process received signal ***
[runnervmw9dnm:10861] Signal: Aborted (6)
[runnervmw9dnm:10861] Signal code:  (-6)
[runnervmw9dnm:10861] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f296f645330]
[runnervmw9dnm:10861] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f296f69eb2c]
[runnervmw9dnm:10861] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f296f64527e]
[runnervmw9dnm:10861] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f296f6288ff]
[runnervmw9dnm:10861] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f296faa5ff5]
[runnervmw9dnm:10861] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f296fabb0da]
[runnervmw9dnm:10861] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f296faa5a55]
[runnervmw9dnm:10861] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f296faa5a6f]
[runnervmw9dnm:10861] [ 8] plumed(+0x146dd)[0x55d5a83406dd]
[runnervmw9dnm:10861] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f296f62a1ca]
[runnervmw9dnm:10861] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f296f62a28b]
[runnervmw9dnm:10861] [11] plumed(+0x15365)[0x55d5a8341365]
[runnervmw9dnm:10861] *** End of error message ***
</pre>
{% endraw %}
