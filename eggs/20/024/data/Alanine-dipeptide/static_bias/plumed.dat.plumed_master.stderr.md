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
[runnervmeorf1:07563] *** Process received signal ***
[runnervmeorf1:07563] Signal: Aborted (6)
[runnervmeorf1:07563] Signal code:  (-6)
[runnervmeorf1:07563] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6c67a45330]
[runnervmeorf1:07563] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6c67a9eb2c]
[runnervmeorf1:07563] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6c67a4527e]
[runnervmeorf1:07563] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6c67a288ff]
[runnervmeorf1:07563] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6c67ea5ff5]
[runnervmeorf1:07563] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6c67ebb0da]
[runnervmeorf1:07563] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6c67ea5a55]
[runnervmeorf1:07563] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6c67ea5a6f]
[runnervmeorf1:07563] [ 8] plumed_master(+0x146dd)[0x563a224766dd]
[runnervmeorf1:07563] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6c67a2a1ca]
[runnervmeorf1:07563] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6c67a2a28b]
[runnervmeorf1:07563] [11] plumed_master(+0x15365)[0x563a22477365]
[runnervmeorf1:07563] *** End of error message ***
</pre>
{% endraw %}
