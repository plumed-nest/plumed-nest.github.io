**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @70 : keyword ARG is compulsory for this action
[runnervm0kj6c:08307] *** Process received signal ***
[runnervm0kj6c:08307] Signal: Aborted (6)
[runnervm0kj6c:08307] Signal code:  (-6)
[runnervm0kj6c:08307] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0bf6c45330]
[runnervm0kj6c:08307] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0bf6c9eb2c]
[runnervm0kj6c:08307] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0bf6c4527e]
[runnervm0kj6c:08307] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0bf6c288ff]
[runnervm0kj6c:08307] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0bf70a5ff5]
[runnervm0kj6c:08307] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0bf70bb0da]
[runnervm0kj6c:08307] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0bf70a5a55]
[runnervm0kj6c:08307] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0bf70a5a6f]
[runnervm0kj6c:08307] [ 8] plumed_master(+0x146dd)[0x55f7436da6dd]
[runnervm0kj6c:08307] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0bf6c2a1ca]
[runnervm0kj6c:08307] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0bf6c2a28b]
[runnervm0kj6c:08307] [11] plumed_master(+0x15365)[0x55f7436db365]
[runnervm0kj6c:08307] *** End of error message ***
</pre>
{% endraw %}
