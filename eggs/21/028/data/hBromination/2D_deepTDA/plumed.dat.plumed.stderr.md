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
[pkrvmf6wy0o8zjz:65549] *** Process received signal ***
[pkrvmf6wy0o8zjz:65549] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65549] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65549] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e44a45330]
[pkrvmf6wy0o8zjz:65549] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e44a9eb2c]
[pkrvmf6wy0o8zjz:65549] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e44a4527e]
[pkrvmf6wy0o8zjz:65549] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e44a288ff]
[pkrvmf6wy0o8zjz:65549] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e44ea5ff5]
[pkrvmf6wy0o8zjz:65549] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e44ebb0da]
[pkrvmf6wy0o8zjz:65549] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e44ea5a55]
[pkrvmf6wy0o8zjz:65549] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e44ea5a6f]
[pkrvmf6wy0o8zjz:65549] [ 8] plumed(+0x146dd)[0x560f819416dd]
[pkrvmf6wy0o8zjz:65549] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e44a2a1ca]
[pkrvmf6wy0o8zjz:65549] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e44a2a28b]
[pkrvmf6wy0o8zjz:65549] [11] plumed(+0x15365)[0x560f81942365]
[pkrvmf6wy0o8zjz:65549] *** End of error message ***
</pre>
{% endraw %}
