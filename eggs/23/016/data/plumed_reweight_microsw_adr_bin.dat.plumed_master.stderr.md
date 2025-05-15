**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:06688] *** Process received signal ***
[pkrvmberfyhpb9w:06688] Signal: Aborted (6)
[pkrvmberfyhpb9w:06688] Signal code:  (-6)
[pkrvmberfyhpb9w:06688] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f448e845330]
[pkrvmberfyhpb9w:06688] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f448e89eb2c]
[pkrvmberfyhpb9w:06688] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f448e84527e]
[pkrvmberfyhpb9w:06688] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f448e8288ff]
[pkrvmberfyhpb9w:06688] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f448eca5ff5]
[pkrvmberfyhpb9w:06688] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f448ecbb0da]
[pkrvmberfyhpb9w:06688] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f448eca5a55]
[pkrvmberfyhpb9w:06688] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f448eca5a6f]
[pkrvmberfyhpb9w:06688] [ 8] plumed_master(+0x146dd)[0x55e53dc3a6dd]
[pkrvmberfyhpb9w:06688] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f448e82a1ca]
[pkrvmberfyhpb9w:06688] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f448e82a28b]
[pkrvmberfyhpb9w:06688] [11] plumed_master(+0x15365)[0x55e53dc3b365]
[pkrvmberfyhpb9w:06688] *** End of error message ***
</pre>
{% endraw %}
