**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmberfyhpb9w:07692] *** Process received signal ***
[pkrvmberfyhpb9w:07692] Signal: Aborted (6)
[pkrvmberfyhpb9w:07692] Signal code:  (-6)
[pkrvmberfyhpb9w:07692] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f16a8a45330]
[pkrvmberfyhpb9w:07692] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f16a8a9eb2c]
[pkrvmberfyhpb9w:07692] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f16a8a4527e]
[pkrvmberfyhpb9w:07692] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f16a8a288ff]
[pkrvmberfyhpb9w:07692] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f16a8ea5ff5]
[pkrvmberfyhpb9w:07692] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f16a8ebb0da]
[pkrvmberfyhpb9w:07692] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f16a8ea5a55]
[pkrvmberfyhpb9w:07692] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f16a8ea5a6f]
[pkrvmberfyhpb9w:07692] [ 8] plumed(+0x146dd)[0x56104e9ee6dd]
[pkrvmberfyhpb9w:07692] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f16a8a2a1ca]
[pkrvmberfyhpb9w:07692] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f16a8a2a28b]
[pkrvmberfyhpb9w:07692] [11] plumed(+0x15365)[0x56104e9ef365]
[pkrvmberfyhpb9w:07692] *** End of error message ***
</pre>
{% endraw %}
