**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmberfyhpb9w:08295] *** Process received signal ***
[pkrvmberfyhpb9w:08295] Signal: Aborted (6)
[pkrvmberfyhpb9w:08295] Signal code:  (-6)
[pkrvmberfyhpb9w:08295] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff35da45330]
[pkrvmberfyhpb9w:08295] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff35da9eb2c]
[pkrvmberfyhpb9w:08295] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff35da4527e]
[pkrvmberfyhpb9w:08295] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff35da288ff]
[pkrvmberfyhpb9w:08295] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff35dea5ff5]
[pkrvmberfyhpb9w:08295] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff35debb0da]
[pkrvmberfyhpb9w:08295] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff35dea5a55]
[pkrvmberfyhpb9w:08295] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff35dea5a6f]
[pkrvmberfyhpb9w:08295] [ 8] plumed_master(+0x146dd)[0x55cee19006dd]
[pkrvmberfyhpb9w:08295] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff35da2a1ca]
[pkrvmberfyhpb9w:08295] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff35da2a28b]
[pkrvmberfyhpb9w:08295] [11] plumed_master(+0x15365)[0x55cee1901365]
[pkrvmberfyhpb9w:08295] *** End of error message ***
</pre>
{% endraw %}
