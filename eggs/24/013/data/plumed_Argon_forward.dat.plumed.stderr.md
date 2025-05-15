**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmberfyhpb9w:07111] *** Process received signal ***
[pkrvmberfyhpb9w:07111] Signal: Aborted (6)
[pkrvmberfyhpb9w:07111] Signal code:  (-6)
[pkrvmberfyhpb9w:07111] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0530a45330]
[pkrvmberfyhpb9w:07111] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0530a9eb2c]
[pkrvmberfyhpb9w:07111] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0530a4527e]
[pkrvmberfyhpb9w:07111] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0530a288ff]
[pkrvmberfyhpb9w:07111] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0530ea5ff5]
[pkrvmberfyhpb9w:07111] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0530ebb0da]
[pkrvmberfyhpb9w:07111] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0530ea5a55]
[pkrvmberfyhpb9w:07111] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0530ea5a6f]
[pkrvmberfyhpb9w:07111] [ 8] plumed(+0x146dd)[0x55f28259f6dd]
[pkrvmberfyhpb9w:07111] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0530a2a1ca]
[pkrvmberfyhpb9w:07111] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0530a2a28b]
[pkrvmberfyhpb9w:07111] [11] plumed(+0x15365)[0x55f2825a0365]
[pkrvmberfyhpb9w:07111] *** End of error message ***
</pre>
{% endraw %}
