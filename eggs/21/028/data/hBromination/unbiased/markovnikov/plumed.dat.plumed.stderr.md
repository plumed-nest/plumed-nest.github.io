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
[runnervmmklqx:07638] *** Process received signal ***
[runnervmmklqx:07638] Signal: Aborted (6)
[runnervmmklqx:07638] Signal code:  (-6)
[runnervmmklqx:07638] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fabee045330]
[runnervmmklqx:07638] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fabee09eb2c]
[runnervmmklqx:07638] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fabee04527e]
[runnervmmklqx:07638] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fabee0288ff]
[runnervmmklqx:07638] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fabee4a5ff5]
[runnervmmklqx:07638] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fabee4bb0da]
[runnervmmklqx:07638] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fabee4a5a55]
[runnervmmklqx:07638] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fabee4a5a6f]
[runnervmmklqx:07638] [ 8] plumed(+0x146dd)[0x557b634836dd]
[runnervmmklqx:07638] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fabee02a1ca]
[runnervmmklqx:07638] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fabee02a28b]
[runnervmmklqx:07638] [11] plumed(+0x15365)[0x557b63484365]
[runnervmmklqx:07638] *** End of error message ***
</pre>
{% endraw %}
