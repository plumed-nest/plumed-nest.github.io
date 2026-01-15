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
[runnervmmtnos:33921] *** Process received signal ***
[runnervmmtnos:33921] Signal: Aborted (6)
[runnervmmtnos:33921] Signal code:  (-6)
[runnervmmtnos:33921] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd8df045330]
[runnervmmtnos:33921] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd8df09eb2c]
[runnervmmtnos:33921] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd8df04527e]
[runnervmmtnos:33921] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8df0288ff]
[runnervmmtnos:33921] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd8df4a5ff5]
[runnervmmtnos:33921] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd8df4bb0da]
[runnervmmtnos:33921] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd8df4a5a55]
[runnervmmtnos:33921] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd8df4a5a6f]
[runnervmmtnos:33921] [ 8] plumed_master(+0x146dd)[0x56414cf206dd]
[runnervmmtnos:33921] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd8df02a1ca]
[runnervmmtnos:33921] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd8df02a28b]
[runnervmmtnos:33921] [11] plumed_master(+0x15365)[0x56414cf21365]
[runnervmmtnos:33921] *** End of error message ***
</pre>
{% endraw %}
