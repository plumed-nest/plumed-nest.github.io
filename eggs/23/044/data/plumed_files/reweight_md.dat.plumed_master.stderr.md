**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervm0kj6c:05120] *** Process received signal ***
[runnervm0kj6c:05120] Signal: Aborted (6)
[runnervm0kj6c:05120] Signal code:  (-6)
[runnervm0kj6c:05120] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2197c45330]
[runnervm0kj6c:05120] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2197c9eb2c]
[runnervm0kj6c:05120] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2197c4527e]
[runnervm0kj6c:05120] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2197c288ff]
[runnervm0kj6c:05120] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f21980a5ff5]
[runnervm0kj6c:05120] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f21980bb0da]
[runnervm0kj6c:05120] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f21980a5a55]
[runnervm0kj6c:05120] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f21980a5a6f]
[runnervm0kj6c:05120] [ 8] plumed_master(+0x146dd)[0x55a0dd1786dd]
[runnervm0kj6c:05120] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2197c2a1ca]
[runnervm0kj6c:05120] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2197c2a28b]
[runnervm0kj6c:05120] [11] plumed_master(+0x15365)[0x55a0dd179365]
[runnervm0kj6c:05120] *** End of error message ***
</pre>
{% endraw %}
