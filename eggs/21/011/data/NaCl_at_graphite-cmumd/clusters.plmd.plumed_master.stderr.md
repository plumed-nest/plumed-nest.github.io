**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[fv-az1344-582:65344] *** Process received signal ***
[fv-az1344-582:65344] Signal: Aborted (6)
[fv-az1344-582:65344] Signal code:  (-6)
[fv-az1344-582:65344] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41c6045330]
[fv-az1344-582:65344] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41c609eb2c]
[fv-az1344-582:65344] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41c604527e]
[fv-az1344-582:65344] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41c60288ff]
[fv-az1344-582:65344] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41c64a5ff5]
[fv-az1344-582:65344] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41c64bb0da]
[fv-az1344-582:65344] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41c64a5a55]
[fv-az1344-582:65344] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41c64a5a6f]
[fv-az1344-582:65344] [ 8] plumed_master(+0x146dd)[0x5599095746dd]
[fv-az1344-582:65344] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41c602a1ca]
[fv-az1344-582:65344] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41c602a28b]
[fv-az1344-582:65344] [11] plumed_master(+0x15365)[0x559909575365]
[fv-az1344-582:65344] *** End of error message ***
</pre>
{% endraw %}
