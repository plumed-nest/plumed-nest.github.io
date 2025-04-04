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
[fv-az805-507:11688] *** Process received signal ***
[fv-az805-507:11688] Signal: Aborted (6)
[fv-az805-507:11688] Signal code:  (-6)
[fv-az805-507:11688] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f037a845330]
[fv-az805-507:11688] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f037a89eb2c]
[fv-az805-507:11688] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f037a84527e]
[fv-az805-507:11688] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f037a8288ff]
[fv-az805-507:11688] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f037aca5ff5]
[fv-az805-507:11688] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f037acbb0da]
[fv-az805-507:11688] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f037aca5a55]
[fv-az805-507:11688] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f037aca5a6f]
[fv-az805-507:11688] [ 8] plumed_master(+0x146dd)[0x55c8ca8776dd]
[fv-az805-507:11688] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f037a82a1ca]
[fv-az805-507:11688] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f037a82a28b]
[fv-az805-507:11688] [11] plumed_master(+0x15365)[0x55c8ca878365]
[fv-az805-507:11688] *** End of error message ***
</pre>
{% endraw %}
