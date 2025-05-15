**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmberfyhpb9w:07795] *** Process received signal ***
[pkrvmberfyhpb9w:07795] Signal: Aborted (6)
[pkrvmberfyhpb9w:07795] Signal code:  (-6)
[pkrvmberfyhpb9w:07795] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc6d645330]
[pkrvmberfyhpb9w:07795] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc6d69eb2c]
[pkrvmberfyhpb9w:07795] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc6d64527e]
[pkrvmberfyhpb9w:07795] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc6d6288ff]
[pkrvmberfyhpb9w:07795] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc6daa5ff5]
[pkrvmberfyhpb9w:07795] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc6dabb0da]
[pkrvmberfyhpb9w:07795] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc6daa5a55]
[pkrvmberfyhpb9w:07795] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc6daa5a6f]
[pkrvmberfyhpb9w:07795] [ 8] plumed(+0x146dd)[0x559e886a26dd]
[pkrvmberfyhpb9w:07795] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc6d62a1ca]
[pkrvmberfyhpb9w:07795] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc6d62a28b]
[pkrvmberfyhpb9w:07795] [11] plumed(+0x15365)[0x559e886a3365]
[pkrvmberfyhpb9w:07795] *** End of error message ***
</pre>
{% endraw %}
