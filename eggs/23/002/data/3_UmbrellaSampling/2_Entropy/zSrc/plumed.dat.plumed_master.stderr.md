**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmberfyhpb9w:07811] *** Process received signal ***
[pkrvmberfyhpb9w:07811] Signal: Aborted (6)
[pkrvmberfyhpb9w:07811] Signal code:  (-6)
[pkrvmberfyhpb9w:07811] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe084045330]
[pkrvmberfyhpb9w:07811] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe08409eb2c]
[pkrvmberfyhpb9w:07811] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe08404527e]
[pkrvmberfyhpb9w:07811] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0840288ff]
[pkrvmberfyhpb9w:07811] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe0844a5ff5]
[pkrvmberfyhpb9w:07811] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe0844bb0da]
[pkrvmberfyhpb9w:07811] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe0844a5a55]
[pkrvmberfyhpb9w:07811] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe0844a5a6f]
[pkrvmberfyhpb9w:07811] [ 8] plumed_master(+0x146dd)[0x558d332526dd]
[pkrvmberfyhpb9w:07811] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe08402a1ca]
[pkrvmberfyhpb9w:07811] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe08402a28b]
[pkrvmberfyhpb9w:07811] [11] plumed_master(+0x15365)[0x558d33253365]
[pkrvmberfyhpb9w:07811] *** End of error message ***
</pre>
{% endraw %}
