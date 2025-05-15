**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmberfyhpb9w:07760] *** Process received signal ***
[pkrvmberfyhpb9w:07760] Signal: Aborted (6)
[pkrvmberfyhpb9w:07760] Signal code:  (-6)
[pkrvmberfyhpb9w:07760] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec5e645330]
[pkrvmberfyhpb9w:07760] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec5e69eb2c]
[pkrvmberfyhpb9w:07760] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec5e64527e]
[pkrvmberfyhpb9w:07760] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec5e6288ff]
[pkrvmberfyhpb9w:07760] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec5eaa5ff5]
[pkrvmberfyhpb9w:07760] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec5eabb0da]
[pkrvmberfyhpb9w:07760] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec5eaa5a55]
[pkrvmberfyhpb9w:07760] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec5eaa5a6f]
[pkrvmberfyhpb9w:07760] [ 8] plumed_master(+0x146dd)[0x557e704386dd]
[pkrvmberfyhpb9w:07760] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec5e62a1ca]
[pkrvmberfyhpb9w:07760] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec5e62a28b]
[pkrvmberfyhpb9w:07760] [11] plumed_master(+0x15365)[0x557e70439365]
[pkrvmberfyhpb9w:07760] *** End of error message ***
</pre>
{% endraw %}
