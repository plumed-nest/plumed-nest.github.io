**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[fv-az1280-696:12006] *** Process received signal ***
[fv-az1280-696:12006] Signal: Aborted (6)
[fv-az1280-696:12006] Signal code:  (-6)
[fv-az1280-696:12006] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8763645330]
[fv-az1280-696:12006] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f876369eb2c]
[fv-az1280-696:12006] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f876364527e]
[fv-az1280-696:12006] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f87636288ff]
[fv-az1280-696:12006] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8763aa5ff5]
[fv-az1280-696:12006] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8763abb0da]
[fv-az1280-696:12006] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8763aa5a55]
[fv-az1280-696:12006] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8763aa5a6f]
[fv-az1280-696:12006] [ 8] plumed_master(+0x146dd)[0x56542d5166dd]
[fv-az1280-696:12006] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f876362a1ca]
[fv-az1280-696:12006] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f876362a28b]
[fv-az1280-696:12006] [11] plumed_master(+0x15365)[0x56542d517365]
[fv-az1280-696:12006] *** End of error message ***
</pre>
{% endraw %}
