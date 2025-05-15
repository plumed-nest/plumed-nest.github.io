**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmberfyhpb9w:08106] *** Process received signal ***
[pkrvmberfyhpb9w:08106] Signal: Aborted (6)
[pkrvmberfyhpb9w:08106] Signal code:  (-6)
[pkrvmberfyhpb9w:08106] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fddd1245330]
[pkrvmberfyhpb9w:08106] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fddd129eb2c]
[pkrvmberfyhpb9w:08106] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fddd124527e]
[pkrvmberfyhpb9w:08106] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fddd12288ff]
[pkrvmberfyhpb9w:08106] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fddd16a5ff5]
[pkrvmberfyhpb9w:08106] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fddd16bb0da]
[pkrvmberfyhpb9w:08106] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fddd16a5a55]
[pkrvmberfyhpb9w:08106] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fddd16a5a6f]
[pkrvmberfyhpb9w:08106] [ 8] plumed_master(+0x146dd)[0x55d1f339c6dd]
[pkrvmberfyhpb9w:08106] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fddd122a1ca]
[pkrvmberfyhpb9w:08106] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fddd122a28b]
[pkrvmberfyhpb9w:08106] [11] plumed_master(+0x15365)[0x55d1f339d365]
[pkrvmberfyhpb9w:08106] *** End of error message ***
</pre>
{% endraw %}
