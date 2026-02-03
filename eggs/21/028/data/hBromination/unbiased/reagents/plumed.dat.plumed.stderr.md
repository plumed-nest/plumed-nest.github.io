**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[runnervmkj6or:11237] *** Process received signal ***
[runnervmkj6or:11237] Signal: Aborted (6)
[runnervmkj6or:11237] Signal code:  (-6)
[runnervmkj6or:11237] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb8fc45330]
[runnervmkj6or:11237] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb8fc9eb2c]
[runnervmkj6or:11237] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb8fc4527e]
[runnervmkj6or:11237] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb8fc288ff]
[runnervmkj6or:11237] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb900a5ff5]
[runnervmkj6or:11237] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb900bb0da]
[runnervmkj6or:11237] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb900a5a55]
[runnervmkj6or:11237] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb900a5a6f]
[runnervmkj6or:11237] [ 8] plumed(+0x146dd)[0x55dfed3d16dd]
[runnervmkj6or:11237] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb8fc2a1ca]
[runnervmkj6or:11237] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb8fc2a28b]
[runnervmkj6or:11237] [11] plumed(+0x15365)[0x55dfed3d2365]
[runnervmkj6or:11237] *** End of error message ***
</pre>
{% endraw %}
