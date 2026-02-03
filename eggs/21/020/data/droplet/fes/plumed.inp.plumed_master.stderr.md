**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervmkj6or:07164] *** Process received signal ***
[runnervmkj6or:07164] Signal: Aborted (6)
[runnervmkj6or:07164] Signal code:  (-6)
[runnervmkj6or:07164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb73a645330]
[runnervmkj6or:07164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb73a69eb2c]
[runnervmkj6or:07164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb73a64527e]
[runnervmkj6or:07164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb73a6288ff]
[runnervmkj6or:07164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb73aaa5ff5]
[runnervmkj6or:07164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb73aabb0da]
[runnervmkj6or:07164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb73aaa5a55]
[runnervmkj6or:07164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb73aaa5a6f]
[runnervmkj6or:07164] [ 8] plumed_master(+0x146dd)[0x55af1be576dd]
[runnervmkj6or:07164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb73a62a1ca]
[runnervmkj6or:07164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb73a62a28b]
[runnervmkj6or:07164] [11] plumed_master(+0x15365)[0x55af1be58365]
[runnervmkj6or:07164] *** End of error message ***
</pre>
{% endraw %}
