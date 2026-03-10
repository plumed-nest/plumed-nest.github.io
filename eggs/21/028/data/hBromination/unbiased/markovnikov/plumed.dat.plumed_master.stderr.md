**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[runnervm0kj6c:10301] *** Process received signal ***
[runnervm0kj6c:10301] Signal: Aborted (6)
[runnervm0kj6c:10301] Signal code:  (-6)
[runnervm0kj6c:10301] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc4d0e45330]
[runnervm0kj6c:10301] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc4d0e9eb2c]
[runnervm0kj6c:10301] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc4d0e4527e]
[runnervm0kj6c:10301] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4d0e288ff]
[runnervm0kj6c:10301] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4d12a5ff5]
[runnervm0kj6c:10301] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4d12bb0da]
[runnervm0kj6c:10301] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4d12a5a55]
[runnervm0kj6c:10301] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4d12a5a6f]
[runnervm0kj6c:10301] [ 8] plumed_master(+0x146dd)[0x56140a5866dd]
[runnervm0kj6c:10301] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc4d0e2a1ca]
[runnervm0kj6c:10301] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc4d0e2a28b]
[runnervm0kj6c:10301] [11] plumed_master(+0x15365)[0x56140a587365]
[runnervm0kj6c:10301] *** End of error message ***
</pre>
{% endraw %}
