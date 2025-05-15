**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmberfyhpb9w:07707] *** Process received signal ***
[pkrvmberfyhpb9w:07707] Signal: Aborted (6)
[pkrvmberfyhpb9w:07707] Signal code:  (-6)
[pkrvmberfyhpb9w:07707] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb082845330]
[pkrvmberfyhpb9w:07707] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb08289eb2c]
[pkrvmberfyhpb9w:07707] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb08284527e]
[pkrvmberfyhpb9w:07707] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0828288ff]
[pkrvmberfyhpb9w:07707] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb082ca5ff5]
[pkrvmberfyhpb9w:07707] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb082cbb0da]
[pkrvmberfyhpb9w:07707] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb082ca5a55]
[pkrvmberfyhpb9w:07707] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb082ca5a6f]
[pkrvmberfyhpb9w:07707] [ 8] plumed_master(+0x146dd)[0x55d68f8566dd]
[pkrvmberfyhpb9w:07707] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb08282a1ca]
[pkrvmberfyhpb9w:07707] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb08282a28b]
[pkrvmberfyhpb9w:07707] [11] plumed_master(+0x15365)[0x55d68f857365]
[pkrvmberfyhpb9w:07707] *** End of error message ***
</pre>
{% endraw %}
