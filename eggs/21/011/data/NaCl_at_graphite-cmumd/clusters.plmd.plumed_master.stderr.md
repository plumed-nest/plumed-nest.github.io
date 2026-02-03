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
[runnervmkj6or:07970] *** Process received signal ***
[runnervmkj6or:07970] Signal: Aborted (6)
[runnervmkj6or:07970] Signal code:  (-6)
[runnervmkj6or:07970] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c83845330]
[runnervmkj6or:07970] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c8389eb2c]
[runnervmkj6or:07970] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c8384527e]
[runnervmkj6or:07970] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c838288ff]
[runnervmkj6or:07970] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c83ca5ff5]
[runnervmkj6or:07970] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c83cbb0da]
[runnervmkj6or:07970] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c83ca5a55]
[runnervmkj6or:07970] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c83ca5a6f]
[runnervmkj6or:07970] [ 8] plumed_master(+0x146dd)[0x55955f1e76dd]
[runnervmkj6or:07970] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c8382a1ca]
[runnervmkj6or:07970] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c8382a28b]
[runnervmkj6or:07970] [11] plumed_master(+0x15365)[0x55955f1e8365]
[runnervmkj6or:07970] *** End of error message ***
</pre>
{% endraw %}
