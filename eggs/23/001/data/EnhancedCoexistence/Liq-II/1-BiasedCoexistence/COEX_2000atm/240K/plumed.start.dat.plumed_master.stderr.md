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
[pkrvmbietmlfzoi:07128] *** Process received signal ***
[pkrvmbietmlfzoi:07128] Signal: Aborted (6)
[pkrvmbietmlfzoi:07128] Signal code:  (-6)
[pkrvmbietmlfzoi:07128] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc817445330]
[pkrvmbietmlfzoi:07128] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc81749eb2c]
[pkrvmbietmlfzoi:07128] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc81744527e]
[pkrvmbietmlfzoi:07128] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc8174288ff]
[pkrvmbietmlfzoi:07128] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8178a5ff5]
[pkrvmbietmlfzoi:07128] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8178bb0da]
[pkrvmbietmlfzoi:07128] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8178a5a55]
[pkrvmbietmlfzoi:07128] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8178a5a6f]
[pkrvmbietmlfzoi:07128] [ 8] plumed_master(+0x146dd)[0x560d32f996dd]
[pkrvmbietmlfzoi:07128] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc81742a1ca]
[pkrvmbietmlfzoi:07128] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc81742a28b]
[pkrvmbietmlfzoi:07128] [11] plumed_master(+0x15365)[0x560d32f9a365]
[pkrvmbietmlfzoi:07128] *** End of error message ***
</pre>
{% endraw %}
