**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmbietmlfzoi:07061] *** Process received signal ***
[pkrvmbietmlfzoi:07061] Signal: Aborted (6)
[pkrvmbietmlfzoi:07061] Signal code:  (-6)
[pkrvmbietmlfzoi:07061] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd3ba845330]
[pkrvmbietmlfzoi:07061] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd3ba89eb2c]
[pkrvmbietmlfzoi:07061] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd3ba84527e]
[pkrvmbietmlfzoi:07061] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3ba8288ff]
[pkrvmbietmlfzoi:07061] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3baca5ff5]
[pkrvmbietmlfzoi:07061] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3bacbb0da]
[pkrvmbietmlfzoi:07061] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3baca5a55]
[pkrvmbietmlfzoi:07061] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3baca5a6f]
[pkrvmbietmlfzoi:07061] [ 8] plumed(+0x146dd)[0x55775c6a86dd]
[pkrvmbietmlfzoi:07061] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd3ba82a1ca]
[pkrvmbietmlfzoi:07061] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd3ba82a28b]
[pkrvmbietmlfzoi:07061] [11] plumed(+0x15365)[0x55775c6a9365]
[pkrvmbietmlfzoi:07061] *** End of error message ***
</pre>
{% endraw %}
