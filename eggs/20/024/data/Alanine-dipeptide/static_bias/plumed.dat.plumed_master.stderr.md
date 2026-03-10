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
[runnervm0kj6c:11262] *** Process received signal ***
[runnervm0kj6c:11262] Signal: Aborted (6)
[runnervm0kj6c:11262] Signal code:  (-6)
[runnervm0kj6c:11262] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ac7045330]
[runnervm0kj6c:11262] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ac709eb2c]
[runnervm0kj6c:11262] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ac704527e]
[runnervm0kj6c:11262] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ac70288ff]
[runnervm0kj6c:11262] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ac74a5ff5]
[runnervm0kj6c:11262] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ac74bb0da]
[runnervm0kj6c:11262] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ac74a5a55]
[runnervm0kj6c:11262] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ac74a5a6f]
[runnervm0kj6c:11262] [ 8] plumed_master(+0x146dd)[0x559cb1bac6dd]
[runnervm0kj6c:11262] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ac702a1ca]
[runnervm0kj6c:11262] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ac702a28b]
[runnervm0kj6c:11262] [11] plumed_master(+0x15365)[0x559cb1bad365]
[runnervm0kj6c:11262] *** End of error message ***
</pre>
{% endraw %}
