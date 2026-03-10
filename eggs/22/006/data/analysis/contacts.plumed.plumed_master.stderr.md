**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @69 : keyword ARG is compulsory for this action
[runnervm0kj6c:08242] *** Process received signal ***
[runnervm0kj6c:08242] Signal: Aborted (6)
[runnervm0kj6c:08242] Signal code:  (-6)
[runnervm0kj6c:08242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb9f5045330]
[runnervm0kj6c:08242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb9f509eb2c]
[runnervm0kj6c:08242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb9f504527e]
[runnervm0kj6c:08242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb9f50288ff]
[runnervm0kj6c:08242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb9f54a5ff5]
[runnervm0kj6c:08242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb9f54bb0da]
[runnervm0kj6c:08242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb9f54a5a55]
[runnervm0kj6c:08242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb9f54a5a6f]
[runnervm0kj6c:08242] [ 8] plumed_master(+0x146dd)[0x556c3944c6dd]
[runnervm0kj6c:08242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb9f502a1ca]
[runnervm0kj6c:08242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb9f502a28b]
[runnervm0kj6c:08242] [11] plumed_master(+0x15365)[0x556c3944d365]
[runnervm0kj6c:08242] *** End of error message ***
</pre>
{% endraw %}
