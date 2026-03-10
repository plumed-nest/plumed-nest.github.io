**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervm0kj6c:06171] *** Process received signal ***
[runnervm0kj6c:06171] Signal: Aborted (6)
[runnervm0kj6c:06171] Signal code:  (-6)
[runnervm0kj6c:06171] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6a7445330]
[runnervm0kj6c:06171] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6a749eb2c]
[runnervm0kj6c:06171] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6a744527e]
[runnervm0kj6c:06171] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6a74288ff]
[runnervm0kj6c:06171] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6a78a5ff5]
[runnervm0kj6c:06171] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6a78bb0da]
[runnervm0kj6c:06171] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6a78a5a55]
[runnervm0kj6c:06171] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6a78a5a6f]
[runnervm0kj6c:06171] [ 8] plumed_master(+0x146dd)[0x55e92f4ba6dd]
[runnervm0kj6c:06171] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6a742a1ca]
[runnervm0kj6c:06171] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6a742a28b]
[runnervm0kj6c:06171] [11] plumed_master(+0x15365)[0x55e92f4bb365]
[runnervm0kj6c:06171] *** End of error message ***
</pre>
{% endraw %}
