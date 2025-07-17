**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmq0rgcvqdmg:09447] *** Process received signal ***
[pkrvmq0rgcvqdmg:09447] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09447] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09447] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f22a45330]
[pkrvmq0rgcvqdmg:09447] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f22a9eb2c]
[pkrvmq0rgcvqdmg:09447] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f22a4527e]
[pkrvmq0rgcvqdmg:09447] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f22a288ff]
[pkrvmq0rgcvqdmg:09447] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f22ea5ff5]
[pkrvmq0rgcvqdmg:09447] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f22ebb0da]
[pkrvmq0rgcvqdmg:09447] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f22ea5a55]
[pkrvmq0rgcvqdmg:09447] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f22ea5a6f]
[pkrvmq0rgcvqdmg:09447] [ 8] plumed_master(+0x146dd)[0x563f667bb6dd]
[pkrvmq0rgcvqdmg:09447] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f22a2a1ca]
[pkrvmq0rgcvqdmg:09447] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f22a2a28b]
[pkrvmq0rgcvqdmg:09447] [11] plumed_master(+0x15365)[0x563f667bc365]
[pkrvmq0rgcvqdmg:09447] *** End of error message ***
</pre>
{% endraw %}
