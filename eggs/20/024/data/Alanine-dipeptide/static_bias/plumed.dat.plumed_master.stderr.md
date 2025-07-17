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
[pkrvmq0rgcvqdmg:09489] *** Process received signal ***
[pkrvmq0rgcvqdmg:09489] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09489] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09489] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f745dc45330]
[pkrvmq0rgcvqdmg:09489] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f745dc9eb2c]
[pkrvmq0rgcvqdmg:09489] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f745dc4527e]
[pkrvmq0rgcvqdmg:09489] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f745dc288ff]
[pkrvmq0rgcvqdmg:09489] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f745e0a5ff5]
[pkrvmq0rgcvqdmg:09489] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f745e0bb0da]
[pkrvmq0rgcvqdmg:09489] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f745e0a5a55]
[pkrvmq0rgcvqdmg:09489] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f745e0a5a6f]
[pkrvmq0rgcvqdmg:09489] [ 8] plumed_master(+0x146dd)[0x5606668ca6dd]
[pkrvmq0rgcvqdmg:09489] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f745dc2a1ca]
[pkrvmq0rgcvqdmg:09489] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f745dc2a28b]
[pkrvmq0rgcvqdmg:09489] [11] plumed_master(+0x15365)[0x5606668cb365]
[pkrvmq0rgcvqdmg:09489] *** End of error message ***
</pre>
{% endraw %}
