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
[pkrvmpptgkbjq6m:11182] *** Process received signal ***
[pkrvmpptgkbjq6m:11182] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11182] Signal code:  (-6)
[pkrvmpptgkbjq6m:11182] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f32f0245330]
[pkrvmpptgkbjq6m:11182] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f32f029eb2c]
[pkrvmpptgkbjq6m:11182] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f32f024527e]
[pkrvmpptgkbjq6m:11182] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f32f02288ff]
[pkrvmpptgkbjq6m:11182] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32f06a5ff5]
[pkrvmpptgkbjq6m:11182] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32f06bb0da]
[pkrvmpptgkbjq6m:11182] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32f06a5a55]
[pkrvmpptgkbjq6m:11182] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32f06a5a6f]
[pkrvmpptgkbjq6m:11182] [ 8] plumed_master(+0x146dd)[0x557845b3f6dd]
[pkrvmpptgkbjq6m:11182] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f32f022a1ca]
[pkrvmpptgkbjq6m:11182] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f32f022a28b]
[pkrvmpptgkbjq6m:11182] [11] plumed_master(+0x15365)[0x557845b40365]
[pkrvmpptgkbjq6m:11182] *** End of error message ***
</pre>
{% endraw %}
