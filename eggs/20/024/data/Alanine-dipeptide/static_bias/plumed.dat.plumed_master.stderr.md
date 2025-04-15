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
[fv-az802-713:65549] *** Process received signal ***
[fv-az802-713:65549] Signal: Aborted (6)
[fv-az802-713:65549] Signal code:  (-6)
[fv-az802-713:65549] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ddcc45330]
[fv-az802-713:65549] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ddcc9eb2c]
[fv-az802-713:65549] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ddcc4527e]
[fv-az802-713:65549] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ddcc288ff]
[fv-az802-713:65549] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ddd0a5ff5]
[fv-az802-713:65549] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ddd0bb0da]
[fv-az802-713:65549] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ddd0a5a55]
[fv-az802-713:65549] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ddd0a5a6f]
[fv-az802-713:65549] [ 8] plumed_master(+0x146dd)[0x559f909bd6dd]
[fv-az802-713:65549] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ddcc2a1ca]
[fv-az802-713:65549] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ddcc2a28b]
[fv-az802-713:65549] [11] plumed_master(+0x15365)[0x559f909be365]
[fv-az802-713:65549] *** End of error message ***
</pre>
{% endraw %}
