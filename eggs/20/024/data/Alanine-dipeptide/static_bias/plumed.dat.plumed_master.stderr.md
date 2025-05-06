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
[fv-az2209-645:67362] *** Process received signal ***
[fv-az2209-645:67362] Signal: Aborted (6)
[fv-az2209-645:67362] Signal code:  (-6)
[fv-az2209-645:67362] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f77c6245330]
[fv-az2209-645:67362] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f77c629eb2c]
[fv-az2209-645:67362] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f77c624527e]
[fv-az2209-645:67362] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77c62288ff]
[fv-az2209-645:67362] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77c66a5ff5]
[fv-az2209-645:67362] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77c66bb0da]
[fv-az2209-645:67362] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77c66a5a55]
[fv-az2209-645:67362] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77c66a5a6f]
[fv-az2209-645:67362] [ 8] plumed_master(+0x146dd)[0x560b22e766dd]
[fv-az2209-645:67362] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f77c622a1ca]
[fv-az2209-645:67362] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f77c622a28b]
[fv-az2209-645:67362] [11] plumed_master(+0x15365)[0x560b22e77365]
[fv-az2209-645:67362] *** End of error message ***
</pre>
{% endraw %}
