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
[runnervmkj6or:11198] *** Process received signal ***
[runnervmkj6or:11198] Signal: Aborted (6)
[runnervmkj6or:11198] Signal code:  (-6)
[runnervmkj6or:11198] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda45645330]
[runnervmkj6or:11198] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda4569eb2c]
[runnervmkj6or:11198] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda4564527e]
[runnervmkj6or:11198] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda456288ff]
[runnervmkj6or:11198] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda45aa5ff5]
[runnervmkj6or:11198] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda45abb0da]
[runnervmkj6or:11198] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda45aa5a55]
[runnervmkj6or:11198] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda45aa5a6f]
[runnervmkj6or:11198] [ 8] plumed_master(+0x146dd)[0x562b24cb76dd]
[runnervmkj6or:11198] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda4562a1ca]
[runnervmkj6or:11198] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda4562a28b]
[runnervmkj6or:11198] [11] plumed_master(+0x15365)[0x562b24cb8365]
[runnervmkj6or:11198] *** End of error message ***
</pre>
{% endraw %}
