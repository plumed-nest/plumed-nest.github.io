**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07417] *** Process received signal ***
[pkrvmberfyhpb9w:07417] Signal: Aborted (6)
[pkrvmberfyhpb9w:07417] Signal code:  (-6)
[pkrvmberfyhpb9w:07417] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f592c645330]
[pkrvmberfyhpb9w:07417] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f592c69eb2c]
[pkrvmberfyhpb9w:07417] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f592c64527e]
[pkrvmberfyhpb9w:07417] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f592c6288ff]
[pkrvmberfyhpb9w:07417] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f592caa5ff5]
[pkrvmberfyhpb9w:07417] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f592cabb0da]
[pkrvmberfyhpb9w:07417] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f592caa5a55]
[pkrvmberfyhpb9w:07417] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f592caa5a6f]
[pkrvmberfyhpb9w:07417] [ 8] plumed_master(+0x146dd)[0x560eb1dab6dd]
[pkrvmberfyhpb9w:07417] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f592c62a1ca]
[pkrvmberfyhpb9w:07417] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f592c62a28b]
[pkrvmberfyhpb9w:07417] [11] plumed_master(+0x15365)[0x560eb1dac365]
[pkrvmberfyhpb9w:07417] *** End of error message ***
</pre>
{% endraw %}
