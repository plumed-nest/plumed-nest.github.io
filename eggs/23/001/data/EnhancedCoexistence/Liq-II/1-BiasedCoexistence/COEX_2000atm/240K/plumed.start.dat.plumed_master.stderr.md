**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmbietmlfzoi:63565] *** Process received signal ***
[pkrvmbietmlfzoi:63565] Signal: Aborted (6)
[pkrvmbietmlfzoi:63565] Signal code:  (-6)
[pkrvmbietmlfzoi:63565] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f94bce45330]
[pkrvmbietmlfzoi:63565] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f94bce9eb2c]
[pkrvmbietmlfzoi:63565] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f94bce4527e]
[pkrvmbietmlfzoi:63565] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94bce288ff]
[pkrvmbietmlfzoi:63565] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94bd2a5ff5]
[pkrvmbietmlfzoi:63565] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94bd2bb0da]
[pkrvmbietmlfzoi:63565] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94bd2a5a55]
[pkrvmbietmlfzoi:63565] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94bd2a5a6f]
[pkrvmbietmlfzoi:63565] [ 8] plumed_master(+0x146dd)[0x55fbb6f846dd]
[pkrvmbietmlfzoi:63565] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f94bce2a1ca]
[pkrvmbietmlfzoi:63565] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f94bce2a28b]
[pkrvmbietmlfzoi:63565] [11] plumed_master(+0x15365)[0x55fbb6f85365]
[pkrvmbietmlfzoi:63565] *** End of error message ***
</pre>
{% endraw %}
