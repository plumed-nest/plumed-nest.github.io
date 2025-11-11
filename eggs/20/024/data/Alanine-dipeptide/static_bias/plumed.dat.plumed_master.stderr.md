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
[runnervmw9dnm:12477] *** Process received signal ***
[runnervmw9dnm:12477] Signal: Aborted (6)
[runnervmw9dnm:12477] Signal code:  (-6)
[runnervmw9dnm:12477] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff1a9e45330]
[runnervmw9dnm:12477] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff1a9e9eb2c]
[runnervmw9dnm:12477] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff1a9e4527e]
[runnervmw9dnm:12477] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1a9e288ff]
[runnervmw9dnm:12477] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1aa2a5ff5]
[runnervmw9dnm:12477] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1aa2bb0da]
[runnervmw9dnm:12477] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1aa2a5a55]
[runnervmw9dnm:12477] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1aa2a5a6f]
[runnervmw9dnm:12477] [ 8] plumed_master(+0x146dd)[0x559724f556dd]
[runnervmw9dnm:12477] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff1a9e2a1ca]
[runnervmw9dnm:12477] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff1a9e2a28b]
[runnervmw9dnm:12477] [11] plumed_master(+0x15365)[0x559724f56365]
[runnervmw9dnm:12477] *** End of error message ***
</pre>
{% endraw %}
