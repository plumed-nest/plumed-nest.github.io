**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[pkrvmberfyhpb9w:07657] *** Process received signal ***
[pkrvmberfyhpb9w:07657] Signal: Aborted (6)
[pkrvmberfyhpb9w:07657] Signal code:  (-6)
[pkrvmberfyhpb9w:07657] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0fe7445330]
[pkrvmberfyhpb9w:07657] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0fe749eb2c]
[pkrvmberfyhpb9w:07657] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0fe744527e]
[pkrvmberfyhpb9w:07657] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0fe74288ff]
[pkrvmberfyhpb9w:07657] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0fe78a5ff5]
[pkrvmberfyhpb9w:07657] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0fe78bb0da]
[pkrvmberfyhpb9w:07657] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0fe78a5a55]
[pkrvmberfyhpb9w:07657] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0fe78a5a6f]
[pkrvmberfyhpb9w:07657] [ 8] plumed_master(+0x146dd)[0x55819c0336dd]
[pkrvmberfyhpb9w:07657] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0fe742a1ca]
[pkrvmberfyhpb9w:07657] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0fe742a28b]
[pkrvmberfyhpb9w:07657] [11] plumed_master(+0x15365)[0x55819c034365]
[pkrvmberfyhpb9w:07657] *** End of error message ***
</pre>
{% endraw %}
