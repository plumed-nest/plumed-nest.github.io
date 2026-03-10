**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm0kj6c:08814] *** Process received signal ***
[runnervm0kj6c:08814] Signal: Aborted (6)
[runnervm0kj6c:08814] Signal code:  (-6)
[runnervm0kj6c:08814] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fccd9445330]
[runnervm0kj6c:08814] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fccd949eb2c]
[runnervm0kj6c:08814] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fccd944527e]
[runnervm0kj6c:08814] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fccd94288ff]
[runnervm0kj6c:08814] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fccd98a5ff5]
[runnervm0kj6c:08814] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fccd98bb0da]
[runnervm0kj6c:08814] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fccd98a5a55]
[runnervm0kj6c:08814] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fccd98a5a6f]
[runnervm0kj6c:08814] [ 8] plumed_master(+0x146dd)[0x5602283146dd]
[runnervm0kj6c:08814] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fccd942a1ca]
[runnervm0kj6c:08814] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fccd942a28b]
[runnervm0kj6c:08814] [11] plumed_master(+0x15365)[0x560228315365]
[runnervm0kj6c:08814] *** End of error message ***
</pre>
{% endraw %}
