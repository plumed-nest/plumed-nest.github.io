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
[pkrvmbietmlfzoi:66739] *** Process received signal ***
[pkrvmbietmlfzoi:66739] Signal: Aborted (6)
[pkrvmbietmlfzoi:66739] Signal code:  (-6)
[pkrvmbietmlfzoi:66739] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8eb0645330]
[pkrvmbietmlfzoi:66739] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8eb069eb2c]
[pkrvmbietmlfzoi:66739] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8eb064527e]
[pkrvmbietmlfzoi:66739] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8eb06288ff]
[pkrvmbietmlfzoi:66739] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8eb0aa5ff5]
[pkrvmbietmlfzoi:66739] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8eb0abb0da]
[pkrvmbietmlfzoi:66739] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8eb0aa5a55]
[pkrvmbietmlfzoi:66739] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8eb0aa5a6f]
[pkrvmbietmlfzoi:66739] [ 8] plumed_master(+0x146dd)[0x558c275a06dd]
[pkrvmbietmlfzoi:66739] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8eb062a1ca]
[pkrvmbietmlfzoi:66739] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8eb062a28b]
[pkrvmbietmlfzoi:66739] [11] plumed_master(+0x15365)[0x558c275a1365]
[pkrvmbietmlfzoi:66739] *** End of error message ***
</pre>
{% endraw %}
