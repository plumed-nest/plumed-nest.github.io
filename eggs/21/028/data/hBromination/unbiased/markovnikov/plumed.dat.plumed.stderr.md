**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[runnervmvrwv9:10518] *** Process received signal ***
[runnervmvrwv9:10518] Signal: Aborted (6)
[runnervmvrwv9:10518] Signal code:  (-6)
[runnervmvrwv9:10518] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fea46045330]
[runnervmvrwv9:10518] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fea4609eb2c]
[runnervmvrwv9:10518] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fea4604527e]
[runnervmvrwv9:10518] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fea460288ff]
[runnervmvrwv9:10518] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fea464a5ff5]
[runnervmvrwv9:10518] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fea464bb0da]
[runnervmvrwv9:10518] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fea464a5a55]
[runnervmvrwv9:10518] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fea464a5a6f]
[runnervmvrwv9:10518] [ 8] plumed(+0x146dd)[0x55a5fcaab6dd]
[runnervmvrwv9:10518] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fea4602a1ca]
[runnervmvrwv9:10518] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fea4602a28b]
[runnervmvrwv9:10518] [11] plumed(+0x15365)[0x55a5fcaac365]
[runnervmvrwv9:10518] *** End of error message ***
</pre>
{% endraw %}
