**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[pkrvmbietmlfzoi:13210] *** Process received signal ***
[pkrvmbietmlfzoi:13210] Signal: Aborted (6)
[pkrvmbietmlfzoi:13210] Signal code:  (-6)
[pkrvmbietmlfzoi:13210] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24a9045330]
[pkrvmbietmlfzoi:13210] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24a909eb2c]
[pkrvmbietmlfzoi:13210] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24a904527e]
[pkrvmbietmlfzoi:13210] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24a90288ff]
[pkrvmbietmlfzoi:13210] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24a94a5ff5]
[pkrvmbietmlfzoi:13210] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24a94bb0da]
[pkrvmbietmlfzoi:13210] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24a94a5a55]
[pkrvmbietmlfzoi:13210] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24a94a5a6f]
[pkrvmbietmlfzoi:13210] [ 8] plumed(+0x146dd)[0x55aec6b8a6dd]
[pkrvmbietmlfzoi:13210] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24a902a1ca]
[pkrvmbietmlfzoi:13210] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24a902a28b]
[pkrvmbietmlfzoi:13210] [11] plumed(+0x15365)[0x55aec6b8b365]
[pkrvmbietmlfzoi:13210] *** End of error message ***
</pre>
{% endraw %}
