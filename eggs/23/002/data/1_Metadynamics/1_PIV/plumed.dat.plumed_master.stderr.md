**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:63036] *** Process received signal ***
[pkrvmbietmlfzoi:63036] Signal: Aborted (6)
[pkrvmbietmlfzoi:63036] Signal code:  (-6)
[pkrvmbietmlfzoi:63036] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f05c3645330]
[pkrvmbietmlfzoi:63036] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f05c369eb2c]
[pkrvmbietmlfzoi:63036] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f05c364527e]
[pkrvmbietmlfzoi:63036] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05c36288ff]
[pkrvmbietmlfzoi:63036] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05c3aa5ff5]
[pkrvmbietmlfzoi:63036] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05c3abb0da]
[pkrvmbietmlfzoi:63036] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05c3aa5a55]
[pkrvmbietmlfzoi:63036] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05c3aa5a6f]
[pkrvmbietmlfzoi:63036] [ 8] plumed_master(+0x146dd)[0x55c0a64926dd]
[pkrvmbietmlfzoi:63036] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f05c362a1ca]
[pkrvmbietmlfzoi:63036] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f05c362a28b]
[pkrvmbietmlfzoi:63036] [11] plumed_master(+0x15365)[0x55c0a6493365]
[pkrvmbietmlfzoi:63036] *** End of error message ***
</pre>
{% endraw %}
