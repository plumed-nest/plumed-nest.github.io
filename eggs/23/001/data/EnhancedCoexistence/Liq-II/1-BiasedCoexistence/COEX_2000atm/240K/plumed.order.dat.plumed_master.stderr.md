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
[pkrvmbietmlfzoi:63513] *** Process received signal ***
[pkrvmbietmlfzoi:63513] Signal: Aborted (6)
[pkrvmbietmlfzoi:63513] Signal code:  (-6)
[pkrvmbietmlfzoi:63513] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2348045330]
[pkrvmbietmlfzoi:63513] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f234809eb2c]
[pkrvmbietmlfzoi:63513] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f234804527e]
[pkrvmbietmlfzoi:63513] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23480288ff]
[pkrvmbietmlfzoi:63513] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23484a5ff5]
[pkrvmbietmlfzoi:63513] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23484bb0da]
[pkrvmbietmlfzoi:63513] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23484a5a55]
[pkrvmbietmlfzoi:63513] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23484a5a6f]
[pkrvmbietmlfzoi:63513] [ 8] plumed_master(+0x146dd)[0x55bf152bc6dd]
[pkrvmbietmlfzoi:63513] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f234802a1ca]
[pkrvmbietmlfzoi:63513] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f234802a28b]
[pkrvmbietmlfzoi:63513] [11] plumed_master(+0x15365)[0x55bf152bd365]
[pkrvmbietmlfzoi:63513] *** End of error message ***
</pre>
{% endraw %}
