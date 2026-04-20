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
[runnervmeorf1:07647] *** Process received signal ***
[runnervmeorf1:07647] Signal: Aborted (6)
[runnervmeorf1:07647] Signal code:  (-6)
[runnervmeorf1:07647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad6ee45330]
[runnervmeorf1:07647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad6ee9eb2c]
[runnervmeorf1:07647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad6ee4527e]
[runnervmeorf1:07647] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad6ee288ff]
[runnervmeorf1:07647] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad6f2a5ff5]
[runnervmeorf1:07647] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad6f2bb0da]
[runnervmeorf1:07647] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad6f2a5a55]
[runnervmeorf1:07647] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad6f2a5a6f]
[runnervmeorf1:07647] [ 8] plumed_master(+0x146dd)[0x561699c086dd]
[runnervmeorf1:07647] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad6ee2a1ca]
[runnervmeorf1:07647] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad6ee2a28b]
[runnervmeorf1:07647] [11] plumed_master(+0x15365)[0x561699c09365]
[runnervmeorf1:07647] *** End of error message ***
</pre>
{% endraw %}
