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
[pkrvmbietmlfzoi:63395] *** Process received signal ***
[pkrvmbietmlfzoi:63395] Signal: Aborted (6)
[pkrvmbietmlfzoi:63395] Signal code:  (-6)
[pkrvmbietmlfzoi:63395] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0800245330]
[pkrvmbietmlfzoi:63395] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f080029eb2c]
[pkrvmbietmlfzoi:63395] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f080024527e]
[pkrvmbietmlfzoi:63395] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f08002288ff]
[pkrvmbietmlfzoi:63395] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f08006a5ff5]
[pkrvmbietmlfzoi:63395] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f08006bb0da]
[pkrvmbietmlfzoi:63395] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f08006a5a55]
[pkrvmbietmlfzoi:63395] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f08006a5a6f]
[pkrvmbietmlfzoi:63395] [ 8] plumed(+0x146dd)[0x5619e01a56dd]
[pkrvmbietmlfzoi:63395] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f080022a1ca]
[pkrvmbietmlfzoi:63395] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f080022a28b]
[pkrvmbietmlfzoi:63395] [11] plumed(+0x15365)[0x5619e01a6365]
[pkrvmbietmlfzoi:63395] *** End of error message ***
</pre>
{% endraw %}
