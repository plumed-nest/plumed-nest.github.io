**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmberfyhpb9w:08279] *** Process received signal ***
[pkrvmberfyhpb9w:08279] Signal: Aborted (6)
[pkrvmberfyhpb9w:08279] Signal code:  (-6)
[pkrvmberfyhpb9w:08279] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb1d6645330]
[pkrvmberfyhpb9w:08279] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb1d669eb2c]
[pkrvmberfyhpb9w:08279] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb1d664527e]
[pkrvmberfyhpb9w:08279] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1d66288ff]
[pkrvmberfyhpb9w:08279] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1d6aa5ff5]
[pkrvmberfyhpb9w:08279] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1d6abb0da]
[pkrvmberfyhpb9w:08279] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1d6aa5a55]
[pkrvmberfyhpb9w:08279] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1d6aa5a6f]
[pkrvmberfyhpb9w:08279] [ 8] plumed(+0x146dd)[0x5595f2c2c6dd]
[pkrvmberfyhpb9w:08279] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb1d662a1ca]
[pkrvmberfyhpb9w:08279] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb1d662a28b]
[pkrvmberfyhpb9w:08279] [11] plumed(+0x15365)[0x5595f2c2d365]
[pkrvmberfyhpb9w:08279] *** End of error message ***
</pre>
{% endraw %}
