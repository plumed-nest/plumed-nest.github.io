**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[pkrvmbietmlfzoi:06966] *** Process received signal ***
[pkrvmbietmlfzoi:06966] Signal: Aborted (6)
[pkrvmbietmlfzoi:06966] Signal code:  (-6)
[pkrvmbietmlfzoi:06966] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9be9045330]
[pkrvmbietmlfzoi:06966] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9be909eb2c]
[pkrvmbietmlfzoi:06966] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9be904527e]
[pkrvmbietmlfzoi:06966] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9be90288ff]
[pkrvmbietmlfzoi:06966] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9be94a5ff5]
[pkrvmbietmlfzoi:06966] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9be94bb0da]
[pkrvmbietmlfzoi:06966] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9be94a5a55]
[pkrvmbietmlfzoi:06966] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9be94a5a6f]
[pkrvmbietmlfzoi:06966] [ 8] plumed_master(+0x146dd)[0x563679bd46dd]
[pkrvmbietmlfzoi:06966] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9be902a1ca]
[pkrvmbietmlfzoi:06966] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9be902a28b]
[pkrvmbietmlfzoi:06966] [11] plumed_master(+0x15365)[0x563679bd5365]
[pkrvmbietmlfzoi:06966] *** End of error message ***
</pre>
{% endraw %}
