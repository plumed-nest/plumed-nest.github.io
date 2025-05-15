**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07455] *** Process received signal ***
[pkrvmberfyhpb9w:07455] Signal: Aborted (6)
[pkrvmberfyhpb9w:07455] Signal code:  (-6)
[pkrvmberfyhpb9w:07455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f762f445330]
[pkrvmberfyhpb9w:07455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f762f49eb2c]
[pkrvmberfyhpb9w:07455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f762f44527e]
[pkrvmberfyhpb9w:07455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f762f4288ff]
[pkrvmberfyhpb9w:07455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f762f8a5ff5]
[pkrvmberfyhpb9w:07455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f762f8bb0da]
[pkrvmberfyhpb9w:07455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f762f8a5a55]
[pkrvmberfyhpb9w:07455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f762f8a5a6f]
[pkrvmberfyhpb9w:07455] [ 8] plumed_master(+0x146dd)[0x55ef45cf96dd]
[pkrvmberfyhpb9w:07455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f762f42a1ca]
[pkrvmberfyhpb9w:07455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f762f42a28b]
[pkrvmberfyhpb9w:07455] [11] plumed_master(+0x15365)[0x55ef45cfa365]
[pkrvmberfyhpb9w:07455] *** End of error message ***
</pre>
{% endraw %}
