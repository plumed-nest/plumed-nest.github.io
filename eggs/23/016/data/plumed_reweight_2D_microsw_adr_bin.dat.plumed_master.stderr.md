**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[runnervm0kj6c:05249] *** Process received signal ***
[runnervm0kj6c:05249] Signal: Aborted (6)
[runnervm0kj6c:05249] Signal code:  (-6)
[runnervm0kj6c:05249] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f57b8845330]
[runnervm0kj6c:05249] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f57b889eb2c]
[runnervm0kj6c:05249] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f57b884527e]
[runnervm0kj6c:05249] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f57b88288ff]
[runnervm0kj6c:05249] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f57b8ca5ff5]
[runnervm0kj6c:05249] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f57b8cbb0da]
[runnervm0kj6c:05249] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f57b8ca5a55]
[runnervm0kj6c:05249] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f57b8ca5a6f]
[runnervm0kj6c:05249] [ 8] plumed_master(+0x146dd)[0x55ee742796dd]
[runnervm0kj6c:05249] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f57b882a1ca]
[runnervm0kj6c:05249] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f57b882a28b]
[runnervm0kj6c:05249] [11] plumed_master(+0x15365)[0x55ee7427a365]
[runnervm0kj6c:05249] *** End of error message ***
</pre>
{% endraw %}
