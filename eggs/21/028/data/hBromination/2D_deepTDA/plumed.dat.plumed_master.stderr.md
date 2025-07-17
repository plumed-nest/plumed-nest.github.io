**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
[pkrvmq0rgcvqdmg:09281] *** Process received signal ***
[pkrvmq0rgcvqdmg:09281] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09281] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09281] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff808c45330]
[pkrvmq0rgcvqdmg:09281] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff808c9eb2c]
[pkrvmq0rgcvqdmg:09281] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff808c4527e]
[pkrvmq0rgcvqdmg:09281] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff808c288ff]
[pkrvmq0rgcvqdmg:09281] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff8090a5ff5]
[pkrvmq0rgcvqdmg:09281] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff8090bb0da]
[pkrvmq0rgcvqdmg:09281] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff8090a5a55]
[pkrvmq0rgcvqdmg:09281] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff8090a5a6f]
[pkrvmq0rgcvqdmg:09281] [ 8] plumed_master(+0x146dd)[0x55b02e6016dd]
[pkrvmq0rgcvqdmg:09281] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff808c2a1ca]
[pkrvmq0rgcvqdmg:09281] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff808c2a28b]
[pkrvmq0rgcvqdmg:09281] [11] plumed_master(+0x15365)[0x55b02e602365]
[pkrvmq0rgcvqdmg:09281] *** End of error message ***
</pre>
{% endraw %}
