**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[pkrvmxyh4eaekms:14082] *** Process received signal ***
[pkrvmxyh4eaekms:14082] Signal: Aborted (6)
[pkrvmxyh4eaekms:14082] Signal code:  (-6)
[pkrvmxyh4eaekms:14082] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf3ce45330]
[pkrvmxyh4eaekms:14082] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf3ce9eb2c]
[pkrvmxyh4eaekms:14082] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf3ce4527e]
[pkrvmxyh4eaekms:14082] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf3ce288ff]
[pkrvmxyh4eaekms:14082] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf3d2a5ff5]
[pkrvmxyh4eaekms:14082] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf3d2bb0da]
[pkrvmxyh4eaekms:14082] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf3d2a5a55]
[pkrvmxyh4eaekms:14082] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf3d2a5a6f]
[pkrvmxyh4eaekms:14082] [ 8] plumed_master(+0x146dd)[0x55747141e6dd]
[pkrvmxyh4eaekms:14082] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf3ce2a1ca]
[pkrvmxyh4eaekms:14082] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf3ce2a28b]
[pkrvmxyh4eaekms:14082] [11] plumed_master(+0x15365)[0x55747141f365]
[pkrvmxyh4eaekms:14082] *** End of error message ***
</pre>
{% endraw %}
