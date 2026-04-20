**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[runnervmeorf1:10196] *** Process received signal ***
[runnervmeorf1:10196] Signal: Aborted (6)
[runnervmeorf1:10196] Signal code:  (-6)
[runnervmeorf1:10196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe89da45330]
[runnervmeorf1:10196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe89da9eb2c]
[runnervmeorf1:10196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe89da4527e]
[runnervmeorf1:10196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe89da288ff]
[runnervmeorf1:10196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe89dea5ff5]
[runnervmeorf1:10196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe89debb0da]
[runnervmeorf1:10196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe89dea5a55]
[runnervmeorf1:10196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe89dea5a6f]
[runnervmeorf1:10196] [ 8] plumed(+0x146dd)[0x5621f76426dd]
[runnervmeorf1:10196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe89da2a1ca]
[runnervmeorf1:10196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe89da2a28b]
[runnervmeorf1:10196] [11] plumed(+0x15365)[0x5621f7643365]
[runnervmeorf1:10196] *** End of error message ***
</pre>
{% endraw %}
