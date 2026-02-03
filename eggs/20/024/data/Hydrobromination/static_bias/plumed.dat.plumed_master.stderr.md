**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Hydrobromination/static_bias/plumed.dat   
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
[runnervmkj6or:09893] *** Process received signal ***
[runnervmkj6or:09893] Signal: Aborted (6)
[runnervmkj6or:09893] Signal code:  (-6)
[runnervmkj6or:09893] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7314045330]
[runnervmkj6or:09893] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f731409eb2c]
[runnervmkj6or:09893] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f731404527e]
[runnervmkj6or:09893] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f73140288ff]
[runnervmkj6or:09893] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73144a5ff5]
[runnervmkj6or:09893] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73144bb0da]
[runnervmkj6or:09893] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73144a5a55]
[runnervmkj6or:09893] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73144a5a6f]
[runnervmkj6or:09893] [ 8] plumed_master(+0x146dd)[0x564db5bd66dd]
[runnervmkj6or:09893] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f731402a1ca]
[runnervmkj6or:09893] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f731402a28b]
[runnervmkj6or:09893] [11] plumed_master(+0x15365)[0x564db5bd7365]
[runnervmkj6or:09893] *** End of error message ***
</pre>
{% endraw %}
