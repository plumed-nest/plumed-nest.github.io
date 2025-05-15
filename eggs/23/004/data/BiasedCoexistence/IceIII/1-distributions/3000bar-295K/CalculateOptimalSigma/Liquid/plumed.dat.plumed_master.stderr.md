**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07533] *** Process received signal ***
[pkrvmberfyhpb9w:07533] Signal: Aborted (6)
[pkrvmberfyhpb9w:07533] Signal code:  (-6)
[pkrvmberfyhpb9w:07533] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24ef045330]
[pkrvmberfyhpb9w:07533] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24ef09eb2c]
[pkrvmberfyhpb9w:07533] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24ef04527e]
[pkrvmberfyhpb9w:07533] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24ef0288ff]
[pkrvmberfyhpb9w:07533] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24ef4a5ff5]
[pkrvmberfyhpb9w:07533] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24ef4bb0da]
[pkrvmberfyhpb9w:07533] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24ef4a5a55]
[pkrvmberfyhpb9w:07533] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24ef4a5a6f]
[pkrvmberfyhpb9w:07533] [ 8] plumed_master(+0x146dd)[0x562e9eb046dd]
[pkrvmberfyhpb9w:07533] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24ef02a1ca]
[pkrvmberfyhpb9w:07533] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24ef02a28b]
[pkrvmberfyhpb9w:07533] [11] plumed_master(+0x15365)[0x562e9eb05365]
[pkrvmberfyhpb9w:07533] *** End of error message ***
</pre>
{% endraw %}
