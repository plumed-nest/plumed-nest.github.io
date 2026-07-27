**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[runnervmvrwv9:08976] *** Process received signal ***
[runnervmvrwv9:08976] Signal: Aborted (6)
[runnervmvrwv9:08976] Signal code:  (-6)
[runnervmvrwv9:08976] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6fee045330]
[runnervmvrwv9:08976] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6fee09eb2c]
[runnervmvrwv9:08976] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6fee04527e]
[runnervmvrwv9:08976] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6fee0288ff]
[runnervmvrwv9:08976] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6fee4a5ff5]
[runnervmvrwv9:08976] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6fee4bb0da]
[runnervmvrwv9:08976] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6fee4a5a55]
[runnervmvrwv9:08976] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6fee4a5a6f]
[runnervmvrwv9:08976] [ 8] plumed_master(+0x146dd)[0x55598311d6dd]
[runnervmvrwv9:08976] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6fee02a1ca]
[runnervmvrwv9:08976] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6fee02a28b]
[runnervmvrwv9:08976] [11] plumed_master(+0x15365)[0x55598311e365]
[runnervmvrwv9:08976] *** End of error message ***
</pre>
{% endraw %}
