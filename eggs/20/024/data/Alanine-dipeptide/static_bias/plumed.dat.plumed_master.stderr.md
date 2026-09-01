**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
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
[runnervmgx7h7:09328] *** Process received signal ***
[runnervmgx7h7:09328] Signal: Aborted (6)
[runnervmgx7h7:09328] Signal code:  (-6)
[runnervmgx7h7:09328] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f66ccc45330]
[runnervmgx7h7:09328] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f66ccc9ec0c]
[runnervmgx7h7:09328] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f66ccc4527e]
[runnervmgx7h7:09328] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66ccc288ff]
[runnervmgx7h7:09328] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66cd0a5ff5]
[runnervmgx7h7:09328] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66cd0bb0da]
[runnervmgx7h7:09328] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66cd0a5a55]
[runnervmgx7h7:09328] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66cd0a5a6f]
[runnervmgx7h7:09328] [ 8] plumed_master(+0x146dd)[0x562f93ff76dd]
[runnervmgx7h7:09328] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f66ccc2a1ca]
[runnervmgx7h7:09328] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f66ccc2a28b]
[runnervmgx7h7:09328] [11] plumed_master(+0x15365)[0x562f93ff8365]
[runnervmgx7h7:09328] *** End of error message ***
</pre>
{% endraw %}
