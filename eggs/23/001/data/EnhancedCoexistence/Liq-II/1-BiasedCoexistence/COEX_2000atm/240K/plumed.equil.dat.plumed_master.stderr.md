**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmberfyhpb9w:08187] *** Process received signal ***
[pkrvmberfyhpb9w:08187] Signal: Aborted (6)
[pkrvmberfyhpb9w:08187] Signal code:  (-6)
[pkrvmberfyhpb9w:08187] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb54845330]
[pkrvmberfyhpb9w:08187] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb5489eb2c]
[pkrvmberfyhpb9w:08187] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb5484527e]
[pkrvmberfyhpb9w:08187] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb548288ff]
[pkrvmberfyhpb9w:08187] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb54ca5ff5]
[pkrvmberfyhpb9w:08187] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb54cbb0da]
[pkrvmberfyhpb9w:08187] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb54ca5a55]
[pkrvmberfyhpb9w:08187] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb54ca5a6f]
[pkrvmberfyhpb9w:08187] [ 8] plumed_master(+0x146dd)[0x5567162906dd]
[pkrvmberfyhpb9w:08187] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb5482a1ca]
[pkrvmberfyhpb9w:08187] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb5482a28b]
[pkrvmberfyhpb9w:08187] [11] plumed_master(+0x15365)[0x556716291365]
[pkrvmberfyhpb9w:08187] *** End of error message ***
</pre>
{% endraw %}
