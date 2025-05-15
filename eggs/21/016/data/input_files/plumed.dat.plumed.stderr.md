**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmberfyhpb9w:11508] *** Process received signal ***
[pkrvmberfyhpb9w:11508] Signal: Aborted (6)
[pkrvmberfyhpb9w:11508] Signal code:  (-6)
[pkrvmberfyhpb9w:11508] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1462045330]
[pkrvmberfyhpb9w:11508] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f146209eb2c]
[pkrvmberfyhpb9w:11508] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f146204527e]
[pkrvmberfyhpb9w:11508] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f14620288ff]
[pkrvmberfyhpb9w:11508] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f14624a5ff5]
[pkrvmberfyhpb9w:11508] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f14624bb0da]
[pkrvmberfyhpb9w:11508] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f14624a5a55]
[pkrvmberfyhpb9w:11508] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f14624a5a6f]
[pkrvmberfyhpb9w:11508] [ 8] plumed(+0x146dd)[0x5631593be6dd]
[pkrvmberfyhpb9w:11508] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f146202a1ca]
[pkrvmberfyhpb9w:11508] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f146202a28b]
[pkrvmberfyhpb9w:11508] [11] plumed(+0x15365)[0x5631593bf365]
[pkrvmberfyhpb9w:11508] *** End of error message ***
</pre>
{% endraw %}
