**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmbietmlfzoi:07077] *** Process received signal ***
[pkrvmbietmlfzoi:07077] Signal: Aborted (6)
[pkrvmbietmlfzoi:07077] Signal code:  (-6)
[pkrvmbietmlfzoi:07077] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2c24e45330]
[pkrvmbietmlfzoi:07077] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2c24e9eb2c]
[pkrvmbietmlfzoi:07077] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2c24e4527e]
[pkrvmbietmlfzoi:07077] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2c24e288ff]
[pkrvmbietmlfzoi:07077] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2c252a5ff5]
[pkrvmbietmlfzoi:07077] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2c252bb0da]
[pkrvmbietmlfzoi:07077] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2c252a5a55]
[pkrvmbietmlfzoi:07077] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2c252a5a6f]
[pkrvmbietmlfzoi:07077] [ 8] plumed_master(+0x146dd)[0x55803c3fd6dd]
[pkrvmbietmlfzoi:07077] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2c24e2a1ca]
[pkrvmbietmlfzoi:07077] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2c24e2a28b]
[pkrvmbietmlfzoi:07077] [11] plumed_master(+0x15365)[0x55803c3fe365]
[pkrvmbietmlfzoi:07077] *** End of error message ***
</pre>
{% endraw %}
