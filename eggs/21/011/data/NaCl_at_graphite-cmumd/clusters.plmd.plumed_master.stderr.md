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
[runnervmeorf1:09303] *** Process received signal ***
[runnervmeorf1:09303] Signal: Aborted (6)
[runnervmeorf1:09303] Signal code:  (-6)
[runnervmeorf1:09303] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab91245330]
[runnervmeorf1:09303] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab9129eb2c]
[runnervmeorf1:09303] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab9124527e]
[runnervmeorf1:09303] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab912288ff]
[runnervmeorf1:09303] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab916a5ff5]
[runnervmeorf1:09303] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab916bb0da]
[runnervmeorf1:09303] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab916a5a55]
[runnervmeorf1:09303] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab916a5a6f]
[runnervmeorf1:09303] [ 8] plumed_master(+0x146dd)[0x55590f1b36dd]
[runnervmeorf1:09303] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab9122a1ca]
[runnervmeorf1:09303] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab9122a28b]
[runnervmeorf1:09303] [11] plumed_master(+0x15365)[0x55590f1b4365]
[runnervmeorf1:09303] *** End of error message ***
</pre>
{% endraw %}
