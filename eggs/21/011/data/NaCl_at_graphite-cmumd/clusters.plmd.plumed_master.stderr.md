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
[fv-az1921-959:67470] *** Process received signal ***
[fv-az1921-959:67470] Signal: Aborted (6)
[fv-az1921-959:67470] Signal code:  (-6)
[fv-az1921-959:67470] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe0dd245330]
[fv-az1921-959:67470] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe0dd29eb2c]
[fv-az1921-959:67470] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe0dd24527e]
[fv-az1921-959:67470] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0dd2288ff]
[fv-az1921-959:67470] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe0dd6a5ff5]
[fv-az1921-959:67470] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe0dd6bb0da]
[fv-az1921-959:67470] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe0dd6a5a55]
[fv-az1921-959:67470] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe0dd6a5a6f]
[fv-az1921-959:67470] [ 8] plumed_master(+0x146dd)[0x5603fe8de6dd]
[fv-az1921-959:67470] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe0dd22a1ca]
[fv-az1921-959:67470] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe0dd22a28b]
[fv-az1921-959:67470] [11] plumed_master(+0x15365)[0x5603fe8df365]
[fv-az1921-959:67470] *** End of error message ***
</pre>
{% endraw %}
