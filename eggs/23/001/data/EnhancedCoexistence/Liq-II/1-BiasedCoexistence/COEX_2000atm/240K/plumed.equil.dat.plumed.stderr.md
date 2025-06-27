**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmbietmlfzoi:63446] *** Process received signal ***
[pkrvmbietmlfzoi:63446] Signal: Aborted (6)
[pkrvmbietmlfzoi:63446] Signal code:  (-6)
[pkrvmbietmlfzoi:63446] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ae0c45330]
[pkrvmbietmlfzoi:63446] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ae0c9eb2c]
[pkrvmbietmlfzoi:63446] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ae0c4527e]
[pkrvmbietmlfzoi:63446] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ae0c288ff]
[pkrvmbietmlfzoi:63446] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ae10a5ff5]
[pkrvmbietmlfzoi:63446] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ae10bb0da]
[pkrvmbietmlfzoi:63446] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ae10a5a55]
[pkrvmbietmlfzoi:63446] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ae10a5a6f]
[pkrvmbietmlfzoi:63446] [ 8] plumed(+0x146dd)[0x5565cdced6dd]
[pkrvmbietmlfzoi:63446] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ae0c2a1ca]
[pkrvmbietmlfzoi:63446] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ae0c2a28b]
[pkrvmbietmlfzoi:63446] [11] plumed(+0x15365)[0x5565cdcee365]
[pkrvmbietmlfzoi:63446] *** End of error message ***
</pre>
{% endraw %}
