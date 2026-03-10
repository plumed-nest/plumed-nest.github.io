**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed_master.stderr.txt.zip) 
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
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervm0kj6c:11382] *** Process received signal ***
[runnervm0kj6c:11382] Signal: Aborted (6)
[runnervm0kj6c:11382] Signal code:  (-6)
[runnervm0kj6c:11382] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0906445330]
[runnervm0kj6c:11382] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f090649eb2c]
[runnervm0kj6c:11382] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f090644527e]
[runnervm0kj6c:11382] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09064288ff]
[runnervm0kj6c:11382] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09068a5ff5]
[runnervm0kj6c:11382] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09068bb0da]
[runnervm0kj6c:11382] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09068a5a55]
[runnervm0kj6c:11382] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09068a5a6f]
[runnervm0kj6c:11382] [ 8] plumed_master(+0x146dd)[0x555a6b1d26dd]
[runnervm0kj6c:11382] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f090642a1ca]
[runnervm0kj6c:11382] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f090642a28b]
[runnervm0kj6c:11382] [11] plumed_master(+0x15365)[0x555a6b1d3365]
[runnervm0kj6c:11382] *** End of error message ***
</pre>
{% endraw %}
