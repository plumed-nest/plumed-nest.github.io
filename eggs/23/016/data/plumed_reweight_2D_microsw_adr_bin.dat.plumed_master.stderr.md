**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:06649] *** Process received signal ***
[pkrvmberfyhpb9w:06649] Signal: Aborted (6)
[pkrvmberfyhpb9w:06649] Signal code:  (-6)
[pkrvmberfyhpb9w:06649] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f72245330]
[pkrvmberfyhpb9w:06649] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f7229eb2c]
[pkrvmberfyhpb9w:06649] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f7224527e]
[pkrvmberfyhpb9w:06649] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f722288ff]
[pkrvmberfyhpb9w:06649] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f726a5ff5]
[pkrvmberfyhpb9w:06649] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f726bb0da]
[pkrvmberfyhpb9w:06649] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f726a5a55]
[pkrvmberfyhpb9w:06649] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f726a5a6f]
[pkrvmberfyhpb9w:06649] [ 8] plumed_master(+0x146dd)[0x55cda7f136dd]
[pkrvmberfyhpb9w:06649] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f7222a1ca]
[pkrvmberfyhpb9w:06649] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f7222a28b]
[pkrvmberfyhpb9w:06649] [11] plumed_master(+0x15365)[0x55cda7f14365]
[pkrvmberfyhpb9w:06649] *** End of error message ***
</pre>
{% endraw %}
