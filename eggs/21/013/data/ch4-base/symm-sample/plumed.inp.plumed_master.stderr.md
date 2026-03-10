**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervm0kj6c:09224] *** Process received signal ***
[runnervm0kj6c:09224] Signal: Aborted (6)
[runnervm0kj6c:09224] Signal code:  (-6)
[runnervm0kj6c:09224] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b7d645330]
[runnervm0kj6c:09224] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b7d69eb2c]
[runnervm0kj6c:09224] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b7d64527e]
[runnervm0kj6c:09224] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b7d6288ff]
[runnervm0kj6c:09224] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b7daa5ff5]
[runnervm0kj6c:09224] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b7dabb0da]
[runnervm0kj6c:09224] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b7daa5a55]
[runnervm0kj6c:09224] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b7daa5a6f]
[runnervm0kj6c:09224] [ 8] plumed_master(+0x146dd)[0x5626a480c6dd]
[runnervm0kj6c:09224] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b7d62a1ca]
[runnervm0kj6c:09224] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b7d62a28b]
[runnervm0kj6c:09224] [11] plumed_master(+0x15365)[0x5626a480d365]
[runnervm0kj6c:09224] *** End of error message ***
</pre>
{% endraw %}
