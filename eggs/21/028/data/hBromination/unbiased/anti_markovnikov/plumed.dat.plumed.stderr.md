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
[runnervmkj6or:11124] *** Process received signal ***
[runnervmkj6or:11124] Signal: Aborted (6)
[runnervmkj6or:11124] Signal code:  (-6)
[runnervmkj6or:11124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f485bc45330]
[runnervmkj6or:11124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f485bc9eb2c]
[runnervmkj6or:11124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f485bc4527e]
[runnervmkj6or:11124] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f485bc288ff]
[runnervmkj6or:11124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f485c0a5ff5]
[runnervmkj6or:11124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f485c0bb0da]
[runnervmkj6or:11124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f485c0a5a55]
[runnervmkj6or:11124] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f485c0a5a6f]
[runnervmkj6or:11124] [ 8] plumed(+0x146dd)[0x5570aa7ac6dd]
[runnervmkj6or:11124] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f485bc2a1ca]
[runnervmkj6or:11124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f485bc2a28b]
[runnervmkj6or:11124] [11] plumed(+0x15365)[0x5570aa7ad365]
[runnervmkj6or:11124] *** End of error message ***
</pre>
{% endraw %}
