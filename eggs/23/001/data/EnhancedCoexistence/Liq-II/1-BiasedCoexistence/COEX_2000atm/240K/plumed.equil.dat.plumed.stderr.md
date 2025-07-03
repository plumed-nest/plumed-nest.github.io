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
[pkrvmbietmlfzoi:07005] *** Process received signal ***
[pkrvmbietmlfzoi:07005] Signal: Aborted (6)
[pkrvmbietmlfzoi:07005] Signal code:  (-6)
[pkrvmbietmlfzoi:07005] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6dca645330]
[pkrvmbietmlfzoi:07005] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6dca69eb2c]
[pkrvmbietmlfzoi:07005] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6dca64527e]
[pkrvmbietmlfzoi:07005] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6dca6288ff]
[pkrvmbietmlfzoi:07005] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6dcaaa5ff5]
[pkrvmbietmlfzoi:07005] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6dcaabb0da]
[pkrvmbietmlfzoi:07005] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6dcaaa5a55]
[pkrvmbietmlfzoi:07005] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6dcaaa5a6f]
[pkrvmbietmlfzoi:07005] [ 8] plumed(+0x146dd)[0x55e6fd3b66dd]
[pkrvmbietmlfzoi:07005] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6dca62a1ca]
[pkrvmbietmlfzoi:07005] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6dca62a28b]
[pkrvmbietmlfzoi:07005] [11] plumed(+0x15365)[0x55e6fd3b7365]
[pkrvmbietmlfzoi:07005] *** End of error message ***
</pre>
{% endraw %}
