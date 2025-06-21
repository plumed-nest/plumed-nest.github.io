**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:13767] *** Process received signal ***
[pkrvmxyh4eaekms:13767] Signal: Aborted (6)
[pkrvmxyh4eaekms:13767] Signal code:  (-6)
[pkrvmxyh4eaekms:13767] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa27ac45330]
[pkrvmxyh4eaekms:13767] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa27ac9eb2c]
[pkrvmxyh4eaekms:13767] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa27ac4527e]
[pkrvmxyh4eaekms:13767] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa27ac288ff]
[pkrvmxyh4eaekms:13767] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa27b0a5ff5]
[pkrvmxyh4eaekms:13767] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa27b0bb0da]
[pkrvmxyh4eaekms:13767] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa27b0a5a55]
[pkrvmxyh4eaekms:13767] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa27b0a5a6f]
[pkrvmxyh4eaekms:13767] [ 8] plumed_master(+0x146dd)[0x55789914d6dd]
[pkrvmxyh4eaekms:13767] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa27ac2a1ca]
[pkrvmxyh4eaekms:13767] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa27ac2a28b]
[pkrvmxyh4eaekms:13767] [11] plumed_master(+0x15365)[0x55789914e365]
[pkrvmxyh4eaekms:13767] *** End of error message ***
</pre>
{% endraw %}
