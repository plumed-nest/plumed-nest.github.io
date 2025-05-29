**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[pkrvmf6wy0o8zjz:65681] *** Process received signal ***
[pkrvmf6wy0o8zjz:65681] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65681] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65681] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f56d6e45330]
[pkrvmf6wy0o8zjz:65681] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f56d6e9eb2c]
[pkrvmf6wy0o8zjz:65681] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f56d6e4527e]
[pkrvmf6wy0o8zjz:65681] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56d6e288ff]
[pkrvmf6wy0o8zjz:65681] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f56d72a5ff5]
[pkrvmf6wy0o8zjz:65681] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f56d72bb0da]
[pkrvmf6wy0o8zjz:65681] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f56d72a5a55]
[pkrvmf6wy0o8zjz:65681] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f56d72a5a6f]
[pkrvmf6wy0o8zjz:65681] [ 8] plumed_master(+0x146dd)[0x55b85f3da6dd]
[pkrvmf6wy0o8zjz:65681] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f56d6e2a1ca]
[pkrvmf6wy0o8zjz:65681] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f56d6e2a28b]
[pkrvmf6wy0o8zjz:65681] [11] plumed_master(+0x15365)[0x55b85f3db365]
[pkrvmf6wy0o8zjz:65681] *** End of error message ***
</pre>
{% endraw %}
