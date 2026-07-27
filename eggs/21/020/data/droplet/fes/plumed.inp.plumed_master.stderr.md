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
[runnervmvrwv9:09448] *** Process received signal ***
[runnervmvrwv9:09448] Signal: Aborted (6)
[runnervmvrwv9:09448] Signal code:  (-6)
[runnervmvrwv9:09448] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ef7045330]
[runnervmvrwv9:09448] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ef709eb2c]
[runnervmvrwv9:09448] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ef704527e]
[runnervmvrwv9:09448] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ef70288ff]
[runnervmvrwv9:09448] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ef74a5ff5]
[runnervmvrwv9:09448] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ef74bb0da]
[runnervmvrwv9:09448] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ef74a5a55]
[runnervmvrwv9:09448] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ef74a5a6f]
[runnervmvrwv9:09448] [ 8] plumed_master(+0x146dd)[0x5651351256dd]
[runnervmvrwv9:09448] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ef702a1ca]
[runnervmvrwv9:09448] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ef702a28b]
[runnervmvrwv9:09448] [11] plumed_master(+0x15365)[0x565135126365]
[runnervmvrwv9:09448] *** End of error message ***
</pre>
{% endraw %}
