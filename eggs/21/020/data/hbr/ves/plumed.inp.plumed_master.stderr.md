**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervm0kj6c:10848] *** Process received signal ***
[runnervm0kj6c:10848] Signal: Aborted (6)
[runnervm0kj6c:10848] Signal code:  (-6)
[runnervm0kj6c:10848] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1025645330]
[runnervm0kj6c:10848] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f102569eb2c]
[runnervm0kj6c:10848] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f102564527e]
[runnervm0kj6c:10848] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10256288ff]
[runnervm0kj6c:10848] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1025aa5ff5]
[runnervm0kj6c:10848] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1025abb0da]
[runnervm0kj6c:10848] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1025aa5a55]
[runnervm0kj6c:10848] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1025aa5a6f]
[runnervm0kj6c:10848] [ 8] plumed_master(+0x146dd)[0x55dc8d74b6dd]
[runnervm0kj6c:10848] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f102562a1ca]
[runnervm0kj6c:10848] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f102562a28b]
[runnervm0kj6c:10848] [11] plumed_master(+0x15365)[0x55dc8d74c365]
[runnervm0kj6c:10848] *** End of error message ***
</pre>
{% endraw %}
