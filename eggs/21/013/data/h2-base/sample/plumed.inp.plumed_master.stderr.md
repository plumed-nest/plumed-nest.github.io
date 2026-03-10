**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @18 : keyword ARG is compulsory for this action
[runnervm0kj6c:09901] *** Process received signal ***
[runnervm0kj6c:09901] Signal: Aborted (6)
[runnervm0kj6c:09901] Signal code:  (-6)
[runnervm0kj6c:09901] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f425f045330]
[runnervm0kj6c:09901] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f425f09eb2c]
[runnervm0kj6c:09901] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f425f04527e]
[runnervm0kj6c:09901] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f425f0288ff]
[runnervm0kj6c:09901] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f425f4a5ff5]
[runnervm0kj6c:09901] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f425f4bb0da]
[runnervm0kj6c:09901] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f425f4a5a55]
[runnervm0kj6c:09901] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f425f4a5a6f]
[runnervm0kj6c:09901] [ 8] plumed_master(+0x146dd)[0x557fee9246dd]
[runnervm0kj6c:09901] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f425f02a1ca]
[runnervm0kj6c:09901] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f425f02a28b]
[runnervm0kj6c:09901] [11] plumed_master(+0x15365)[0x557fee925365]
[runnervm0kj6c:09901] *** End of error message ***
</pre>
{% endraw %}
