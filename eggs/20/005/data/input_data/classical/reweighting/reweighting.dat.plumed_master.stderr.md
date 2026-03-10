**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @19 : keyword ARG is compulsory for this action
[runnervm0kj6c:11865] *** Process received signal ***
[runnervm0kj6c:11865] Signal: Aborted (6)
[runnervm0kj6c:11865] Signal code:  (-6)
[runnervm0kj6c:11865] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1258445330]
[runnervm0kj6c:11865] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f125849eb2c]
[runnervm0kj6c:11865] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f125844527e]
[runnervm0kj6c:11865] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12584288ff]
[runnervm0kj6c:11865] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12588a5ff5]
[runnervm0kj6c:11865] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12588bb0da]
[runnervm0kj6c:11865] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12588a5a55]
[runnervm0kj6c:11865] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12588a5a6f]
[runnervm0kj6c:11865] [ 8] plumed_master(+0x146dd)[0x55c2f6fe16dd]
[runnervm0kj6c:11865] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f125842a1ca]
[runnervm0kj6c:11865] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f125842a28b]
[runnervm0kj6c:11865] [11] plumed_master(+0x15365)[0x55c2f6fe2365]
[runnervm0kj6c:11865] *** End of error message ***
</pre>
{% endraw %}
