**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmberfyhpb9w:08242] *** Process received signal ***
[pkrvmberfyhpb9w:08242] Signal: Aborted (6)
[pkrvmberfyhpb9w:08242] Signal code:  (-6)
[pkrvmberfyhpb9w:08242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f01e1c45330]
[pkrvmberfyhpb9w:08242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f01e1c9eb2c]
[pkrvmberfyhpb9w:08242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f01e1c4527e]
[pkrvmberfyhpb9w:08242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01e1c288ff]
[pkrvmberfyhpb9w:08242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01e20a5ff5]
[pkrvmberfyhpb9w:08242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01e20bb0da]
[pkrvmberfyhpb9w:08242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01e20a5a55]
[pkrvmberfyhpb9w:08242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01e20a5a6f]
[pkrvmberfyhpb9w:08242] [ 8] plumed_master(+0x146dd)[0x55fda6dc16dd]
[pkrvmberfyhpb9w:08242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f01e1c2a1ca]
[pkrvmberfyhpb9w:08242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f01e1c2a28b]
[pkrvmberfyhpb9w:08242] [11] plumed_master(+0x15365)[0x55fda6dc2365]
[pkrvmberfyhpb9w:08242] *** End of error message ***
</pre>
{% endraw %}
