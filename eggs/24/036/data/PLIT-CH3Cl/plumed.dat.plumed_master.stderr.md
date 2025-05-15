**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:05964] *** Process received signal ***
[pkrvmberfyhpb9w:05964] Signal: Aborted (6)
[pkrvmberfyhpb9w:05964] Signal code:  (-6)
[pkrvmberfyhpb9w:05964] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc652a45330]
[pkrvmberfyhpb9w:05964] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc652a9eb2c]
[pkrvmberfyhpb9w:05964] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc652a4527e]
[pkrvmberfyhpb9w:05964] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc652a288ff]
[pkrvmberfyhpb9w:05964] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc652ea5ff5]
[pkrvmberfyhpb9w:05964] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc652ebb0da]
[pkrvmberfyhpb9w:05964] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc652ea5a55]
[pkrvmberfyhpb9w:05964] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc652ea5a6f]
[pkrvmberfyhpb9w:05964] [ 8] plumed_master(+0x146dd)[0x55d56e0c16dd]
[pkrvmberfyhpb9w:05964] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc652a2a1ca]
[pkrvmberfyhpb9w:05964] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc652a2a28b]
[pkrvmberfyhpb9w:05964] [11] plumed_master(+0x15365)[0x55d56e0c2365]
[pkrvmberfyhpb9w:05964] *** End of error message ***
</pre>
{% endraw %}
