**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07495] *** Process received signal ***
[pkrvmberfyhpb9w:07495] Signal: Aborted (6)
[pkrvmberfyhpb9w:07495] Signal code:  (-6)
[pkrvmberfyhpb9w:07495] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa64ec45330]
[pkrvmberfyhpb9w:07495] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa64ec9eb2c]
[pkrvmberfyhpb9w:07495] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa64ec4527e]
[pkrvmberfyhpb9w:07495] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa64ec288ff]
[pkrvmberfyhpb9w:07495] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa64f0a5ff5]
[pkrvmberfyhpb9w:07495] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa64f0bb0da]
[pkrvmberfyhpb9w:07495] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa64f0a5a55]
[pkrvmberfyhpb9w:07495] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa64f0a5a6f]
[pkrvmberfyhpb9w:07495] [ 8] plumed_master(+0x146dd)[0x564cf824c6dd]
[pkrvmberfyhpb9w:07495] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa64ec2a1ca]
[pkrvmberfyhpb9w:07495] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa64ec2a28b]
[pkrvmberfyhpb9w:07495] [11] plumed_master(+0x15365)[0x564cf824d365]
[pkrvmberfyhpb9w:07495] *** End of error message ***
</pre>
{% endraw %}
