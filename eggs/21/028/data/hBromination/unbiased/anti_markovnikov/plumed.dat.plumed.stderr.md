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
[runnervm0kj6c:10226] *** Process received signal ***
[runnervm0kj6c:10226] Signal: Aborted (6)
[runnervm0kj6c:10226] Signal code:  (-6)
[runnervm0kj6c:10226] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3163245330]
[runnervm0kj6c:10226] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f316329eb2c]
[runnervm0kj6c:10226] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f316324527e]
[runnervm0kj6c:10226] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31632288ff]
[runnervm0kj6c:10226] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f31636a5ff5]
[runnervm0kj6c:10226] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f31636bb0da]
[runnervm0kj6c:10226] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f31636a5a55]
[runnervm0kj6c:10226] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f31636a5a6f]
[runnervm0kj6c:10226] [ 8] plumed(+0x146dd)[0x563e9413e6dd]
[runnervm0kj6c:10226] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f316322a1ca]
[runnervm0kj6c:10226] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f316322a28b]
[runnervm0kj6c:10226] [11] plumed(+0x15365)[0x563e9413f365]
[runnervm0kj6c:10226] *** End of error message ***
</pre>
{% endraw %}
