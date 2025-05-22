**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:461) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmf6wy0o8zjz:36585] *** Process received signal ***
[pkrvmf6wy0o8zjz:36585] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:36585] Signal code:  (-6)
[pkrvmf6wy0o8zjz:36585] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e28245330]
[pkrvmf6wy0o8zjz:36585] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e2829eb2c]
[pkrvmf6wy0o8zjz:36585] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e2824527e]
[pkrvmf6wy0o8zjz:36585] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e282288ff]
[pkrvmf6wy0o8zjz:36585] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e286a5ff5]
[pkrvmf6wy0o8zjz:36585] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e286bb0da]
[pkrvmf6wy0o8zjz:36585] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e286a5a55]
[pkrvmf6wy0o8zjz:36585] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e286a5a6f]
[pkrvmf6wy0o8zjz:36585] [ 8] plumed_master(+0x146dd)[0x5636adb666dd]
[pkrvmf6wy0o8zjz:36585] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e2822a1ca]
[pkrvmf6wy0o8zjz:36585] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e2822a28b]
[pkrvmf6wy0o8zjz:36585] [11] plumed_master(+0x15365)[0x5636adb67365]
[pkrvmf6wy0o8zjz:36585] *** End of error message ***
</pre>
{% endraw %}
