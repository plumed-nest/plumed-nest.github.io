**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[pkrvmberfyhpb9w:08118] *** Process received signal ***
[pkrvmberfyhpb9w:08118] Signal: Aborted (6)
[pkrvmberfyhpb9w:08118] Signal code:  (-6)
[pkrvmberfyhpb9w:08118] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2e50c45330]
[pkrvmberfyhpb9w:08118] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2e50c9eb2c]
[pkrvmberfyhpb9w:08118] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2e50c4527e]
[pkrvmberfyhpb9w:08118] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2e50c288ff]
[pkrvmberfyhpb9w:08118] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2e510a5ff5]
[pkrvmberfyhpb9w:08118] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2e510bb0da]
[pkrvmberfyhpb9w:08118] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2e510a5a55]
[pkrvmberfyhpb9w:08118] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2e510a5a6f]
[pkrvmberfyhpb9w:08118] [ 8] plumed(+0x146dd)[0x558c7dc1c6dd]
[pkrvmberfyhpb9w:08118] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2e50c2a1ca]
[pkrvmberfyhpb9w:08118] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2e50c2a28b]
[pkrvmberfyhpb9w:08118] [11] plumed(+0x15365)[0x558c7dc1d365]
[pkrvmberfyhpb9w:08118] *** End of error message ***
</pre>
{% endraw %}
