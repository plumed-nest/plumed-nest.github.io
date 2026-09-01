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
[runnervmgx7h7:08322] *** Process received signal ***
[runnervmgx7h7:08322] Signal: Aborted (6)
[runnervmgx7h7:08322] Signal code:  (-6)
[runnervmgx7h7:08322] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc0b5e45330]
[runnervmgx7h7:08322] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc0b5e9ec0c]
[runnervmgx7h7:08322] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc0b5e4527e]
[runnervmgx7h7:08322] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0b5e288ff]
[runnervmgx7h7:08322] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0b62a5ff5]
[runnervmgx7h7:08322] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0b62bb0da]
[runnervmgx7h7:08322] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0b62a5a55]
[runnervmgx7h7:08322] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0b62a5a6f]
[runnervmgx7h7:08322] [ 8] plumed_master(+0x146dd)[0x560ff46006dd]
[runnervmgx7h7:08322] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc0b5e2a1ca]
[runnervmgx7h7:08322] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc0b5e2a28b]
[runnervmgx7h7:08322] [11] plumed_master(+0x15365)[0x560ff4601365]
[runnervmgx7h7:08322] *** End of error message ***
</pre>
{% endraw %}
