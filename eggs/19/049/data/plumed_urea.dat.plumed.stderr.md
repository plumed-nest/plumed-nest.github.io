**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[pkrvmberfyhpb9w:11136] *** Process received signal ***
[pkrvmberfyhpb9w:11136] Signal: Aborted (6)
[pkrvmberfyhpb9w:11136] Signal code:  (-6)
[pkrvmberfyhpb9w:11136] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa169a45330]
[pkrvmberfyhpb9w:11136] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa169a9eb2c]
[pkrvmberfyhpb9w:11136] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa169a4527e]
[pkrvmberfyhpb9w:11136] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa169a288ff]
[pkrvmberfyhpb9w:11136] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa169ea5ff5]
[pkrvmberfyhpb9w:11136] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa169ebb0da]
[pkrvmberfyhpb9w:11136] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa169ea5a55]
[pkrvmberfyhpb9w:11136] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa169ea5a6f]
[pkrvmberfyhpb9w:11136] [ 8] plumed(+0x146dd)[0x56344825a6dd]
[pkrvmberfyhpb9w:11136] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa169a2a1ca]
[pkrvmberfyhpb9w:11136] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa169a2a28b]
[pkrvmberfyhpb9w:11136] [11] plumed(+0x15365)[0x56344825b365]
[pkrvmberfyhpb9w:11136] *** End of error message ***
</pre>
{% endraw %}
