**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[runnervm0kj6c:10931] *** Process received signal ***
[runnervm0kj6c:10931] Signal: Aborted (6)
[runnervm0kj6c:10931] Signal code:  (-6)
[runnervm0kj6c:10931] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d7f645330]
[runnervm0kj6c:10931] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d7f69eb2c]
[runnervm0kj6c:10931] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d7f64527e]
[runnervm0kj6c:10931] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d7f6288ff]
[runnervm0kj6c:10931] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d7faa5ff5]
[runnervm0kj6c:10931] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d7fabb0da]
[runnervm0kj6c:10931] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d7faa5a55]
[runnervm0kj6c:10931] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d7faa5a6f]
[runnervm0kj6c:10931] [ 8] plumed_master(+0x146dd)[0x5622e01f76dd]
[runnervm0kj6c:10931] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d7f62a1ca]
[runnervm0kj6c:10931] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d7f62a28b]
[runnervm0kj6c:10931] [11] plumed_master(+0x15365)[0x5622e01f8365]
[runnervm0kj6c:10931] *** End of error message ***
</pre>
{% endraw %}
