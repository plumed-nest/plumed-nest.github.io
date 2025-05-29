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
[pkrvmf6wy0o8zjz:65624] *** Process received signal ***
[pkrvmf6wy0o8zjz:65624] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65624] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65624] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c89045330]
[pkrvmf6wy0o8zjz:65624] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c8909eb2c]
[pkrvmf6wy0o8zjz:65624] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c8904527e]
[pkrvmf6wy0o8zjz:65624] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c890288ff]
[pkrvmf6wy0o8zjz:65624] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c894a5ff5]
[pkrvmf6wy0o8zjz:65624] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c894bb0da]
[pkrvmf6wy0o8zjz:65624] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c894a5a55]
[pkrvmf6wy0o8zjz:65624] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c894a5a6f]
[pkrvmf6wy0o8zjz:65624] [ 8] plumed_master(+0x146dd)[0x55b41df6a6dd]
[pkrvmf6wy0o8zjz:65624] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c8902a1ca]
[pkrvmf6wy0o8zjz:65624] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c8902a28b]
[pkrvmf6wy0o8zjz:65624] [11] plumed_master(+0x15365)[0x55b41df6b365]
[pkrvmf6wy0o8zjz:65624] *** End of error message ***
</pre>
{% endraw %}
