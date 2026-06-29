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
[runnervmmklqx:07583] *** Process received signal ***
[runnervmmklqx:07583] Signal: Aborted (6)
[runnervmmklqx:07583] Signal code:  (-6)
[runnervmmklqx:07583] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c0b645330]
[runnervmmklqx:07583] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c0b69eb2c]
[runnervmmklqx:07583] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c0b64527e]
[runnervmmklqx:07583] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c0b6288ff]
[runnervmmklqx:07583] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c0baa5ff5]
[runnervmmklqx:07583] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c0babb0da]
[runnervmmklqx:07583] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c0baa5a55]
[runnervmmklqx:07583] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c0baa5a6f]
[runnervmmklqx:07583] [ 8] plumed(+0x146dd)[0x55de5afc06dd]
[runnervmmklqx:07583] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c0b62a1ca]
[runnervmmklqx:07583] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c0b62a28b]
[runnervmmklqx:07583] [11] plumed(+0x15365)[0x55de5afc1365]
[runnervmmklqx:07583] *** End of error message ***
</pre>
{% endraw %}
