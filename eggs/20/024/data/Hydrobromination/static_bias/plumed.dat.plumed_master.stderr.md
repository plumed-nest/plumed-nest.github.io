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
[pkrvmxyh4eaekms:14166] *** Process received signal ***
[pkrvmxyh4eaekms:14166] Signal: Aborted (6)
[pkrvmxyh4eaekms:14166] Signal code:  (-6)
[pkrvmxyh4eaekms:14166] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc4e845330]
[pkrvmxyh4eaekms:14166] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc4e89eb2c]
[pkrvmxyh4eaekms:14166] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc4e84527e]
[pkrvmxyh4eaekms:14166] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc4e8288ff]
[pkrvmxyh4eaekms:14166] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc4eca5ff5]
[pkrvmxyh4eaekms:14166] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc4ecbb0da]
[pkrvmxyh4eaekms:14166] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc4eca5a55]
[pkrvmxyh4eaekms:14166] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc4eca5a6f]
[pkrvmxyh4eaekms:14166] [ 8] plumed_master(+0x146dd)[0x56467380b6dd]
[pkrvmxyh4eaekms:14166] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc4e82a1ca]
[pkrvmxyh4eaekms:14166] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc4e82a28b]
[pkrvmxyh4eaekms:14166] [11] plumed_master(+0x15365)[0x56467380c365]
[pkrvmxyh4eaekms:14166] *** End of error message ***
</pre>
{% endraw %}
