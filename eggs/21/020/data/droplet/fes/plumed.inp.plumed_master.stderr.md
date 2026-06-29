**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervmmklqx:09064] *** Process received signal ***
[runnervmmklqx:09064] Signal: Aborted (6)
[runnervmmklqx:09064] Signal code:  (-6)
[runnervmmklqx:09064] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3beba45330]
[runnervmmklqx:09064] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3beba9eb2c]
[runnervmmklqx:09064] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3beba4527e]
[runnervmmklqx:09064] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3beba288ff]
[runnervmmklqx:09064] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3bebea5ff5]
[runnervmmklqx:09064] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3bebebb0da]
[runnervmmklqx:09064] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3bebea5a55]
[runnervmmklqx:09064] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3bebea5a6f]
[runnervmmklqx:09064] [ 8] plumed_master(+0x146dd)[0x5573cbd0a6dd]
[runnervmmklqx:09064] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3beba2a1ca]
[runnervmmklqx:09064] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3beba2a28b]
[runnervmmklqx:09064] [11] plumed_master(+0x15365)[0x5573cbd0b365]
[runnervmmklqx:09064] *** End of error message ***
</pre>
{% endraw %}
