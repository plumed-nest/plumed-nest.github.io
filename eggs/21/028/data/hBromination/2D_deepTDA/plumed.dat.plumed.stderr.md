**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
[runnervm0kj6c:10168] *** Process received signal ***
[runnervm0kj6c:10168] Signal: Aborted (6)
[runnervm0kj6c:10168] Signal code:  (-6)
[runnervm0kj6c:10168] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee9ee45330]
[runnervm0kj6c:10168] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee9ee9eb2c]
[runnervm0kj6c:10168] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee9ee4527e]
[runnervm0kj6c:10168] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee9ee288ff]
[runnervm0kj6c:10168] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee9f2a5ff5]
[runnervm0kj6c:10168] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee9f2bb0da]
[runnervm0kj6c:10168] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee9f2a5a55]
[runnervm0kj6c:10168] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee9f2a5a6f]
[runnervm0kj6c:10168] [ 8] plumed(+0x146dd)[0x55f80b1896dd]
[runnervm0kj6c:10168] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee9ee2a1ca]
[runnervm0kj6c:10168] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee9ee2a28b]
[runnervm0kj6c:10168] [11] plumed(+0x15365)[0x55f80b18a365]
[runnervm0kj6c:10168] *** End of error message ***
</pre>
{% endraw %}
