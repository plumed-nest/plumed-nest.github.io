**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervm0kj6c:10522] *** Process received signal ***
[runnervm0kj6c:10522] Signal: Aborted (6)
[runnervm0kj6c:10522] Signal code:  (-6)
[runnervm0kj6c:10522] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7001e45330]
[runnervm0kj6c:10522] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7001e9eb2c]
[runnervm0kj6c:10522] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7001e4527e]
[runnervm0kj6c:10522] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7001e288ff]
[runnervm0kj6c:10522] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f70022a5ff5]
[runnervm0kj6c:10522] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f70022bb0da]
[runnervm0kj6c:10522] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f70022a5a55]
[runnervm0kj6c:10522] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f70022a5a6f]
[runnervm0kj6c:10522] [ 8] plumed_master(+0x146dd)[0x564f92a6d6dd]
[runnervm0kj6c:10522] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7001e2a1ca]
[runnervm0kj6c:10522] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7001e2a28b]
[runnervm0kj6c:10522] [11] plumed_master(+0x15365)[0x564f92a6e365]
[runnervm0kj6c:10522] *** End of error message ***
</pre>
{% endraw %}
