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
[runnervm0kj6c:10185] *** Process received signal ***
[runnervm0kj6c:10185] Signal: Aborted (6)
[runnervm0kj6c:10185] Signal code:  (-6)
[runnervm0kj6c:10185] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa89c445330]
[runnervm0kj6c:10185] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa89c49eb2c]
[runnervm0kj6c:10185] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa89c44527e]
[runnervm0kj6c:10185] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa89c4288ff]
[runnervm0kj6c:10185] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa89c8a5ff5]
[runnervm0kj6c:10185] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa89c8bb0da]
[runnervm0kj6c:10185] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa89c8a5a55]
[runnervm0kj6c:10185] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa89c8a5a6f]
[runnervm0kj6c:10185] [ 8] plumed_master(+0x146dd)[0x5556a14846dd]
[runnervm0kj6c:10185] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa89c42a1ca]
[runnervm0kj6c:10185] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa89c42a28b]
[runnervm0kj6c:10185] [11] plumed_master(+0x15365)[0x5556a1485365]
[runnervm0kj6c:10185] *** End of error message ***
</pre>
{% endraw %}
