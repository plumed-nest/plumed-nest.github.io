**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmberfyhpb9w:07075] *** Process received signal ***
[pkrvmberfyhpb9w:07075] Signal: Aborted (6)
[pkrvmberfyhpb9w:07075] Signal code:  (-6)
[pkrvmberfyhpb9w:07075] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41d1a45330]
[pkrvmberfyhpb9w:07075] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41d1a9eb2c]
[pkrvmberfyhpb9w:07075] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41d1a4527e]
[pkrvmberfyhpb9w:07075] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41d1a288ff]
[pkrvmberfyhpb9w:07075] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41d1ea5ff5]
[pkrvmberfyhpb9w:07075] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41d1ebb0da]
[pkrvmberfyhpb9w:07075] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41d1ea5a55]
[pkrvmberfyhpb9w:07075] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41d1ea5a6f]
[pkrvmberfyhpb9w:07075] [ 8] plumed_master(+0x146dd)[0x5618d26d76dd]
[pkrvmberfyhpb9w:07075] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41d1a2a1ca]
[pkrvmberfyhpb9w:07075] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41d1a2a28b]
[pkrvmberfyhpb9w:07075] [11] plumed_master(+0x15365)[0x5618d26d8365]
[pkrvmberfyhpb9w:07075] *** End of error message ***
</pre>
{% endraw %}
