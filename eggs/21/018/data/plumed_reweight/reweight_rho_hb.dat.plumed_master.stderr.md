**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervm0kj6c:08102] *** Process received signal ***
[runnervm0kj6c:08102] Signal: Aborted (6)
[runnervm0kj6c:08102] Signal code:  (-6)
[runnervm0kj6c:08102] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f543da45330]
[runnervm0kj6c:08102] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f543da9eb2c]
[runnervm0kj6c:08102] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f543da4527e]
[runnervm0kj6c:08102] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f543da288ff]
[runnervm0kj6c:08102] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f543dea5ff5]
[runnervm0kj6c:08102] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f543debb0da]
[runnervm0kj6c:08102] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f543dea5a55]
[runnervm0kj6c:08102] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f543dea5a6f]
[runnervm0kj6c:08102] [ 8] plumed_master(+0x146dd)[0x55e2f0d2d6dd]
[runnervm0kj6c:08102] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f543da2a1ca]
[runnervm0kj6c:08102] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f543da2a28b]
[runnervm0kj6c:08102] [11] plumed_master(+0x15365)[0x55e2f0d2e365]
[runnervm0kj6c:08102] *** End of error message ***
</pre>
{% endraw %}
