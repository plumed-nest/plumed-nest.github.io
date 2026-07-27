**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Hydrobromination/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervmvrwv9:11048] *** Process received signal ***
[runnervmvrwv9:11048] Signal: Aborted (6)
[runnervmvrwv9:11048] Signal code:  (-6)
[runnervmvrwv9:11048] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e10e45330]
[runnervmvrwv9:11048] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e10e9eb2c]
[runnervmvrwv9:11048] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e10e4527e]
[runnervmvrwv9:11048] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e10e288ff]
[runnervmvrwv9:11048] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e112a5ff5]
[runnervmvrwv9:11048] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e112bb0da]
[runnervmvrwv9:11048] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e112a5a55]
[runnervmvrwv9:11048] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e112a5a6f]
[runnervmvrwv9:11048] [ 8] plumed_master(+0x146dd)[0x5597595af6dd]
[runnervmvrwv9:11048] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e10e2a1ca]
[runnervmvrwv9:11048] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e10e2a28b]
[runnervmvrwv9:11048] [11] plumed_master(+0x15365)[0x5597595b0365]
[runnervmvrwv9:11048] *** End of error message ***
</pre>
{% endraw %}
