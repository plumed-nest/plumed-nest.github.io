**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az2209-645:64592] *** Process received signal ***
[fv-az2209-645:64592] Signal: Aborted (6)
[fv-az2209-645:64592] Signal code:  (-6)
[fv-az2209-645:64592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2663a45330]
[fv-az2209-645:64592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2663a9eb2c]
[fv-az2209-645:64592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2663a4527e]
[fv-az2209-645:64592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2663a288ff]
[fv-az2209-645:64592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2663ea5ff5]
[fv-az2209-645:64592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2663ebb0da]
[fv-az2209-645:64592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2663ea5a55]
[fv-az2209-645:64592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2663ea5a6f]
[fv-az2209-645:64592] [ 8] plumed_master(+0x146dd)[0x56044738b6dd]
[fv-az2209-645:64592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2663a2a1ca]
[fv-az2209-645:64592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2663a2a28b]
[fv-az2209-645:64592] [11] plumed_master(+0x15365)[0x56044738c365]
[fv-az2209-645:64592] *** End of error message ***
</pre>
{% endraw %}
