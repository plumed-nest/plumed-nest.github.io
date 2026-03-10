**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervm0kj6c:10763] *** Process received signal ***
[runnervm0kj6c:10763] Signal: Aborted (6)
[runnervm0kj6c:10763] Signal code:  (-6)
[runnervm0kj6c:10763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc904645330]
[runnervm0kj6c:10763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc90469eb2c]
[runnervm0kj6c:10763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc90464527e]
[runnervm0kj6c:10763] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9046288ff]
[runnervm0kj6c:10763] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc904aa5ff5]
[runnervm0kj6c:10763] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc904abb0da]
[runnervm0kj6c:10763] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc904aa5a55]
[runnervm0kj6c:10763] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc904aa5a6f]
[runnervm0kj6c:10763] [ 8] plumed_master(+0x146dd)[0x55f7af9dd6dd]
[runnervm0kj6c:10763] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc90462a1ca]
[runnervm0kj6c:10763] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc90462a28b]
[runnervm0kj6c:10763] [11] plumed_master(+0x15365)[0x55f7af9de365]
[runnervm0kj6c:10763] *** End of error message ***
</pre>
{% endraw %}
