**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[runnervmvrwv9:10463] *** Process received signal ***
[runnervmvrwv9:10463] Signal: Aborted (6)
[runnervmvrwv9:10463] Signal code:  (-6)
[runnervmvrwv9:10463] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8992045330]
[runnervmvrwv9:10463] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f899209eb2c]
[runnervmvrwv9:10463] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f899204527e]
[runnervmvrwv9:10463] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f89920288ff]
[runnervmvrwv9:10463] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f89924a5ff5]
[runnervmvrwv9:10463] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f89924bb0da]
[runnervmvrwv9:10463] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f89924a5a55]
[runnervmvrwv9:10463] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f89924a5a6f]
[runnervmvrwv9:10463] [ 8] plumed(+0x146dd)[0x558f0e7186dd]
[runnervmvrwv9:10463] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f899202a1ca]
[runnervmvrwv9:10463] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f899202a28b]
[runnervmvrwv9:10463] [11] plumed(+0x15365)[0x558f0e719365]
[runnervmvrwv9:10463] *** End of error message ***
</pre>
{% endraw %}
