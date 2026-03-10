**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervm0kj6c:10810] *** Process received signal ***
[runnervm0kj6c:10810] Signal: Aborted (6)
[runnervm0kj6c:10810] Signal code:  (-6)
[runnervm0kj6c:10810] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a82e45330]
[runnervm0kj6c:10810] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a82e9eb2c]
[runnervm0kj6c:10810] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a82e4527e]
[runnervm0kj6c:10810] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a82e288ff]
[runnervm0kj6c:10810] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a832a5ff5]
[runnervm0kj6c:10810] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a832bb0da]
[runnervm0kj6c:10810] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a832a5a55]
[runnervm0kj6c:10810] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a832a5a6f]
[runnervm0kj6c:10810] [ 8] plumed_master(+0x146dd)[0x55e0befbe6dd]
[runnervm0kj6c:10810] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a82e2a1ca]
[runnervm0kj6c:10810] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a82e2a28b]
[runnervm0kj6c:10810] [11] plumed_master(+0x15365)[0x55e0befbf365]
[runnervm0kj6c:10810] *** End of error message ***
</pre>
{% endraw %}
