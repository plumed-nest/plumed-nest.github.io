**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
[pkrvmf6wy0o8zjz:36528] *** Process received signal ***
[pkrvmf6wy0o8zjz:36528] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:36528] Signal code:  (-6)
[pkrvmf6wy0o8zjz:36528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac53c45330]
[pkrvmf6wy0o8zjz:36528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac53c9eb2c]
[pkrvmf6wy0o8zjz:36528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac53c4527e]
[pkrvmf6wy0o8zjz:36528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac53c288ff]
[pkrvmf6wy0o8zjz:36528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac540a5ff5]
[pkrvmf6wy0o8zjz:36528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac540bb0da]
[pkrvmf6wy0o8zjz:36528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac540a5a55]
[pkrvmf6wy0o8zjz:36528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac540a5a6f]
[pkrvmf6wy0o8zjz:36528] [ 8] plumed_master(+0x146dd)[0x5615d7ba46dd]
[pkrvmf6wy0o8zjz:36528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac53c2a1ca]
[pkrvmf6wy0o8zjz:36528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac53c2a28b]
[pkrvmf6wy0o8zjz:36528] [11] plumed_master(+0x15365)[0x5615d7ba5365]
[pkrvmf6wy0o8zjz:36528] *** End of error message ***
</pre>
{% endraw %}
