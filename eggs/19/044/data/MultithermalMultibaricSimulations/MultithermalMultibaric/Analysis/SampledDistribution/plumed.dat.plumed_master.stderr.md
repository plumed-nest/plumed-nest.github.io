**Project ID:** [plumID:19.044]({{ '/' | absolute_url }}eggs/19/044/)  
Stderr for source:  MultithermalMultibaricSimulations/MultithermalMultibaric/Analysis/SampledDistribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:12002] *** Process received signal ***
[pkrvmberfyhpb9w:12002] Signal: Aborted (6)
[pkrvmberfyhpb9w:12002] Signal code:  (-6)
[pkrvmberfyhpb9w:12002] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f109d845330]
[pkrvmberfyhpb9w:12002] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f109d89eb2c]
[pkrvmberfyhpb9w:12002] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f109d84527e]
[pkrvmberfyhpb9w:12002] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f109d8288ff]
[pkrvmberfyhpb9w:12002] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f109dca5ff5]
[pkrvmberfyhpb9w:12002] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f109dcbb0da]
[pkrvmberfyhpb9w:12002] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f109dca5a55]
[pkrvmberfyhpb9w:12002] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f109dca5a6f]
[pkrvmberfyhpb9w:12002] [ 8] plumed_master(+0x146dd)[0x55942cfeb6dd]
[pkrvmberfyhpb9w:12002] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f109d82a1ca]
[pkrvmberfyhpb9w:12002] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f109d82a28b]
[pkrvmberfyhpb9w:12002] [11] plumed_master(+0x15365)[0x55942cfec365]
[pkrvmberfyhpb9w:12002] *** End of error message ***
</pre>
{% endraw %}
