**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[pkrvmbietmlfzoi:68193] *** Process received signal ***
[pkrvmbietmlfzoi:68193] Signal: Aborted (6)
[pkrvmbietmlfzoi:68193] Signal code:  (-6)
[pkrvmbietmlfzoi:68193] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1c08245330]
[pkrvmbietmlfzoi:68193] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1c0829eb2c]
[pkrvmbietmlfzoi:68193] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1c0824527e]
[pkrvmbietmlfzoi:68193] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1c082288ff]
[pkrvmbietmlfzoi:68193] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1c086a5ff5]
[pkrvmbietmlfzoi:68193] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1c086bb0da]
[pkrvmbietmlfzoi:68193] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1c086a5a55]
[pkrvmbietmlfzoi:68193] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1c086a5a6f]
[pkrvmbietmlfzoi:68193] [ 8] plumed_master(+0x146dd)[0x55b938ef46dd]
[pkrvmbietmlfzoi:68193] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1c0822a1ca]
[pkrvmbietmlfzoi:68193] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1c0822a28b]
[pkrvmbietmlfzoi:68193] [11] plumed_master(+0x15365)[0x55b938ef5365]
[pkrvmbietmlfzoi:68193] *** End of error message ***
</pre>
{% endraw %}
