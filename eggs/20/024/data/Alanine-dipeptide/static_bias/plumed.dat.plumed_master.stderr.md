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
[pkrvmf6wy0o8zjz:68097] *** Process received signal ***
[pkrvmf6wy0o8zjz:68097] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68097] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68097] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f657ec45330]
[pkrvmf6wy0o8zjz:68097] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f657ec9eb2c]
[pkrvmf6wy0o8zjz:68097] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f657ec4527e]
[pkrvmf6wy0o8zjz:68097] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f657ec288ff]
[pkrvmf6wy0o8zjz:68097] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f657f0a5ff5]
[pkrvmf6wy0o8zjz:68097] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f657f0bb0da]
[pkrvmf6wy0o8zjz:68097] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f657f0a5a55]
[pkrvmf6wy0o8zjz:68097] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f657f0a5a6f]
[pkrvmf6wy0o8zjz:68097] [ 8] plumed_master(+0x146dd)[0x561cb98cd6dd]
[pkrvmf6wy0o8zjz:68097] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f657ec2a1ca]
[pkrvmf6wy0o8zjz:68097] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f657ec2a28b]
[pkrvmf6wy0o8zjz:68097] [11] plumed_master(+0x15365)[0x561cb98ce365]
[pkrvmf6wy0o8zjz:68097] *** End of error message ***
</pre>
{% endraw %}
