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
[pkrvmbietmlfzoi:63411] *** Process received signal ***
[pkrvmbietmlfzoi:63411] Signal: Aborted (6)
[pkrvmbietmlfzoi:63411] Signal code:  (-6)
[pkrvmbietmlfzoi:63411] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ebd845330]
[pkrvmbietmlfzoi:63411] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ebd89eb2c]
[pkrvmbietmlfzoi:63411] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ebd84527e]
[pkrvmbietmlfzoi:63411] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ebd8288ff]
[pkrvmbietmlfzoi:63411] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ebdca5ff5]
[pkrvmbietmlfzoi:63411] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ebdcbb0da]
[pkrvmbietmlfzoi:63411] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ebdca5a55]
[pkrvmbietmlfzoi:63411] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ebdca5a6f]
[pkrvmbietmlfzoi:63411] [ 8] plumed_master(+0x146dd)[0x563e7011d6dd]
[pkrvmbietmlfzoi:63411] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ebd82a1ca]
[pkrvmbietmlfzoi:63411] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ebd82a28b]
[pkrvmbietmlfzoi:63411] [11] plumed_master(+0x15365)[0x563e7011e365]
[pkrvmbietmlfzoi:63411] *** End of error message ***
</pre>
{% endraw %}
