**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm0kj6c:08708] *** Process received signal ***
[runnervm0kj6c:08708] Signal: Aborted (6)
[runnervm0kj6c:08708] Signal code:  (-6)
[runnervm0kj6c:08708] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1ae3c45330]
[runnervm0kj6c:08708] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1ae3c9eb2c]
[runnervm0kj6c:08708] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1ae3c4527e]
[runnervm0kj6c:08708] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1ae3c288ff]
[runnervm0kj6c:08708] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ae40a5ff5]
[runnervm0kj6c:08708] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ae40bb0da]
[runnervm0kj6c:08708] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ae40a5a55]
[runnervm0kj6c:08708] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ae40a5a6f]
[runnervm0kj6c:08708] [ 8] plumed_master(+0x146dd)[0x55d2159186dd]
[runnervm0kj6c:08708] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1ae3c2a1ca]
[runnervm0kj6c:08708] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1ae3c2a28b]
[runnervm0kj6c:08708] [11] plumed_master(+0x15365)[0x55d215919365]
[runnervm0kj6c:08708] *** End of error message ***
</pre>
{% endraw %}
