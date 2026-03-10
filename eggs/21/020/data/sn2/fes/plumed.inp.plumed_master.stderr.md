**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[runnervm0kj6c:10655] *** Process received signal ***
[runnervm0kj6c:10655] Signal: Aborted (6)
[runnervm0kj6c:10655] Signal code:  (-6)
[runnervm0kj6c:10655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb110445330]
[runnervm0kj6c:10655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb11049eb2c]
[runnervm0kj6c:10655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb11044527e]
[runnervm0kj6c:10655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1104288ff]
[runnervm0kj6c:10655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1108a5ff5]
[runnervm0kj6c:10655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1108bb0da]
[runnervm0kj6c:10655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1108a5a55]
[runnervm0kj6c:10655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1108a5a6f]
[runnervm0kj6c:10655] [ 8] plumed_master(+0x146dd)[0x562084c406dd]
[runnervm0kj6c:10655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb11042a1ca]
[runnervm0kj6c:10655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb11042a28b]
[runnervm0kj6c:10655] [11] plumed_master(+0x15365)[0x562084c41365]
[runnervm0kj6c:10655] *** End of error message ***
</pre>
{% endraw %}
