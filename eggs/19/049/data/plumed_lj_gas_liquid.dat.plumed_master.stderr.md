**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:11104] *** Process received signal ***
[pkrvmberfyhpb9w:11104] Signal: Aborted (6)
[pkrvmberfyhpb9w:11104] Signal code:  (-6)
[pkrvmberfyhpb9w:11104] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0701e45330]
[pkrvmberfyhpb9w:11104] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0701e9eb2c]
[pkrvmberfyhpb9w:11104] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0701e4527e]
[pkrvmberfyhpb9w:11104] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0701e288ff]
[pkrvmberfyhpb9w:11104] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07022a5ff5]
[pkrvmberfyhpb9w:11104] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07022bb0da]
[pkrvmberfyhpb9w:11104] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07022a5a55]
[pkrvmberfyhpb9w:11104] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07022a5a6f]
[pkrvmberfyhpb9w:11104] [ 8] plumed_master(+0x146dd)[0x55ce68bfe6dd]
[pkrvmberfyhpb9w:11104] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0701e2a1ca]
[pkrvmberfyhpb9w:11104] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0701e2a28b]
[pkrvmberfyhpb9w:11104] [11] plumed_master(+0x15365)[0x55ce68bff365]
[pkrvmberfyhpb9w:11104] *** End of error message ***
</pre>
{% endraw %}
