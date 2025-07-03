**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmbietmlfzoi:07021] *** Process received signal ***
[pkrvmbietmlfzoi:07021] Signal: Aborted (6)
[pkrvmbietmlfzoi:07021] Signal code:  (-6)
[pkrvmbietmlfzoi:07021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb17f445330]
[pkrvmbietmlfzoi:07021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb17f49eb2c]
[pkrvmbietmlfzoi:07021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb17f44527e]
[pkrvmbietmlfzoi:07021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb17f4288ff]
[pkrvmbietmlfzoi:07021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb17f8a5ff5]
[pkrvmbietmlfzoi:07021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb17f8bb0da]
[pkrvmbietmlfzoi:07021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb17f8a5a55]
[pkrvmbietmlfzoi:07021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb17f8a5a6f]
[pkrvmbietmlfzoi:07021] [ 8] plumed_master(+0x146dd)[0x55dcc40406dd]
[pkrvmbietmlfzoi:07021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb17f42a1ca]
[pkrvmbietmlfzoi:07021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb17f42a28b]
[pkrvmbietmlfzoi:07021] [11] plumed_master(+0x15365)[0x55dcc4041365]
[pkrvmbietmlfzoi:07021] *** End of error message ***
</pre>
{% endraw %}
