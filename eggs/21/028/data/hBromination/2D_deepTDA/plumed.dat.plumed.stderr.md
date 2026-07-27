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
[runnervmvrwv9:10408] *** Process received signal ***
[runnervmvrwv9:10408] Signal: Aborted (6)
[runnervmvrwv9:10408] Signal code:  (-6)
[runnervmvrwv9:10408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f80e2e45330]
[runnervmvrwv9:10408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f80e2e9eb2c]
[runnervmvrwv9:10408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f80e2e4527e]
[runnervmvrwv9:10408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80e2e288ff]
[runnervmvrwv9:10408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f80e32a5ff5]
[runnervmvrwv9:10408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f80e32bb0da]
[runnervmvrwv9:10408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f80e32a5a55]
[runnervmvrwv9:10408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f80e32a5a6f]
[runnervmvrwv9:10408] [ 8] plumed(+0x146dd)[0x5629575ef6dd]
[runnervmvrwv9:10408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f80e2e2a1ca]
[runnervmvrwv9:10408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f80e2e2a28b]
[runnervmvrwv9:10408] [11] plumed(+0x15365)[0x5629575f0365]
[runnervmvrwv9:10408] *** End of error message ***
</pre>
{% endraw %}
