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
[pkrvmf6wy0o8zjz:36677] *** Process received signal ***
[pkrvmf6wy0o8zjz:36677] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:36677] Signal code:  (-6)
[pkrvmf6wy0o8zjz:36677] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c5de45330]
[pkrvmf6wy0o8zjz:36677] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c5de9eb2c]
[pkrvmf6wy0o8zjz:36677] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c5de4527e]
[pkrvmf6wy0o8zjz:36677] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c5de288ff]
[pkrvmf6wy0o8zjz:36677] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c5e2a5ff5]
[pkrvmf6wy0o8zjz:36677] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c5e2bb0da]
[pkrvmf6wy0o8zjz:36677] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c5e2a5a55]
[pkrvmf6wy0o8zjz:36677] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c5e2a5a6f]
[pkrvmf6wy0o8zjz:36677] [ 8] plumed(+0x146dd)[0x563e3cf6e6dd]
[pkrvmf6wy0o8zjz:36677] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c5de2a1ca]
[pkrvmf6wy0o8zjz:36677] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c5de2a28b]
[pkrvmf6wy0o8zjz:36677] [11] plumed(+0x15365)[0x563e3cf6f365]
[pkrvmf6wy0o8zjz:36677] *** End of error message ***
</pre>
{% endraw %}
