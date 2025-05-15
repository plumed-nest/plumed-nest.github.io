**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[pkrvmberfyhpb9w:12633] *** Process received signal ***
[pkrvmberfyhpb9w:12633] Signal: Aborted (6)
[pkrvmberfyhpb9w:12633] Signal code:  (-6)
[pkrvmberfyhpb9w:12633] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8faf445330]
[pkrvmberfyhpb9w:12633] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8faf49eb2c]
[pkrvmberfyhpb9w:12633] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8faf44527e]
[pkrvmberfyhpb9w:12633] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8faf4288ff]
[pkrvmberfyhpb9w:12633] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8faf8a5ff5]
[pkrvmberfyhpb9w:12633] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8faf8bb0da]
[pkrvmberfyhpb9w:12633] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8faf8a5a55]
[pkrvmberfyhpb9w:12633] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8faf8a5a6f]
[pkrvmberfyhpb9w:12633] [ 8] plumed(+0x146dd)[0x55c7a12606dd]
[pkrvmberfyhpb9w:12633] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8faf42a1ca]
[pkrvmberfyhpb9w:12633] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8faf42a28b]
[pkrvmberfyhpb9w:12633] [11] plumed(+0x15365)[0x55c7a1261365]
[pkrvmberfyhpb9w:12633] *** End of error message ***
</pre>
{% endraw %}
