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
[runnervmkj6or:11068] *** Process received signal ***
[runnervmkj6or:11068] Signal: Aborted (6)
[runnervmkj6or:11068] Signal code:  (-6)
[runnervmkj6or:11068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f801c245330]
[runnervmkj6or:11068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f801c29eb2c]
[runnervmkj6or:11068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f801c24527e]
[runnervmkj6or:11068] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f801c2288ff]
[runnervmkj6or:11068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f801c6a5ff5]
[runnervmkj6or:11068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f801c6bb0da]
[runnervmkj6or:11068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f801c6a5a55]
[runnervmkj6or:11068] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f801c6a5a6f]
[runnervmkj6or:11068] [ 8] plumed(+0x146dd)[0x55bb3542d6dd]
[runnervmkj6or:11068] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f801c22a1ca]
[runnervmkj6or:11068] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f801c22a28b]
[runnervmkj6or:11068] [11] plumed(+0x15365)[0x55bb3542e365]
[runnervmkj6or:11068] *** End of error message ***
</pre>
{% endraw %}
