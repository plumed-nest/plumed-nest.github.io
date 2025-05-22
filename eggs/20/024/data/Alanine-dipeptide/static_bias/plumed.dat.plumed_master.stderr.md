**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[pkrvmf6wy0o8zjz:38981] *** Process received signal ***
[pkrvmf6wy0o8zjz:38981] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38981] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38981] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7db5845330]
[pkrvmf6wy0o8zjz:38981] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7db589eb2c]
[pkrvmf6wy0o8zjz:38981] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7db584527e]
[pkrvmf6wy0o8zjz:38981] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7db58288ff]
[pkrvmf6wy0o8zjz:38981] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7db5ca5ff5]
[pkrvmf6wy0o8zjz:38981] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7db5cbb0da]
[pkrvmf6wy0o8zjz:38981] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7db5ca5a55]
[pkrvmf6wy0o8zjz:38981] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7db5ca5a6f]
[pkrvmf6wy0o8zjz:38981] [ 8] plumed_master(+0x146dd)[0x559bc22356dd]
[pkrvmf6wy0o8zjz:38981] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7db582a1ca]
[pkrvmf6wy0o8zjz:38981] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7db582a28b]
[pkrvmf6wy0o8zjz:38981] [11] plumed_master(+0x15365)[0x559bc2236365]
[pkrvmf6wy0o8zjz:38981] *** End of error message ***
</pre>
{% endraw %}
