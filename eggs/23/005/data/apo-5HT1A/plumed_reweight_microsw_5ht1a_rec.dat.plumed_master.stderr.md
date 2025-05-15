**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @117 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07370] *** Process received signal ***
[pkrvmberfyhpb9w:07370] Signal: Aborted (6)
[pkrvmberfyhpb9w:07370] Signal code:  (-6)
[pkrvmberfyhpb9w:07370] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ab8845330]
[pkrvmberfyhpb9w:07370] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ab889eb2c]
[pkrvmberfyhpb9w:07370] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ab884527e]
[pkrvmberfyhpb9w:07370] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ab88288ff]
[pkrvmberfyhpb9w:07370] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ab8ca5ff5]
[pkrvmberfyhpb9w:07370] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ab8cbb0da]
[pkrvmberfyhpb9w:07370] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ab8ca5a55]
[pkrvmberfyhpb9w:07370] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ab8ca5a6f]
[pkrvmberfyhpb9w:07370] [ 8] plumed_master(+0x146dd)[0x56421214a6dd]
[pkrvmberfyhpb9w:07370] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ab882a1ca]
[pkrvmberfyhpb9w:07370] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ab882a28b]
[pkrvmberfyhpb9w:07370] [11] plumed_master(+0x15365)[0x56421214b365]
[pkrvmberfyhpb9w:07370] *** End of error message ***
</pre>
{% endraw %}
