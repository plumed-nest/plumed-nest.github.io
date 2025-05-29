**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[pkrvmf6wy0o8zjz:65737] *** Process received signal ***
[pkrvmf6wy0o8zjz:65737] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65737] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65737] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b85245330]
[pkrvmf6wy0o8zjz:65737] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b8529eb2c]
[pkrvmf6wy0o8zjz:65737] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b8524527e]
[pkrvmf6wy0o8zjz:65737] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b852288ff]
[pkrvmf6wy0o8zjz:65737] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b856a5ff5]
[pkrvmf6wy0o8zjz:65737] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b856bb0da]
[pkrvmf6wy0o8zjz:65737] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b856a5a55]
[pkrvmf6wy0o8zjz:65737] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b856a5a6f]
[pkrvmf6wy0o8zjz:65737] [ 8] plumed_master(+0x146dd)[0x55a8cbc1c6dd]
[pkrvmf6wy0o8zjz:65737] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b8522a1ca]
[pkrvmf6wy0o8zjz:65737] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b8522a28b]
[pkrvmf6wy0o8zjz:65737] [11] plumed_master(+0x15365)[0x55a8cbc1d365]
[pkrvmf6wy0o8zjz:65737] *** End of error message ***
</pre>
{% endraw %}
