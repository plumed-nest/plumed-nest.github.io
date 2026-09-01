**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmgx7h7:08650] *** Process received signal ***
[runnervmgx7h7:08650] Signal: Aborted (6)
[runnervmgx7h7:08650] Signal code:  (-6)
[runnervmgx7h7:08650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efec4645330]
[runnervmgx7h7:08650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efec469ec0c]
[runnervmgx7h7:08650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efec464527e]
[runnervmgx7h7:08650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efec46288ff]
[runnervmgx7h7:08650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efec4aa5ff5]
[runnervmgx7h7:08650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efec4abb0da]
[runnervmgx7h7:08650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efec4aa5a55]
[runnervmgx7h7:08650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efec4aa5a6f]
[runnervmgx7h7:08650] [ 8] plumed(+0x146dd)[0x5624903996dd]
[runnervmgx7h7:08650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efec462a1ca]
[runnervmgx7h7:08650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efec462a28b]
[runnervmgx7h7:08650] [11] plumed(+0x15365)[0x56249039a365]
[runnervmgx7h7:08650] *** End of error message ***
</pre>
{% endraw %}
