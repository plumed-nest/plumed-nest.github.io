**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:08514] *** Process received signal ***
[pkrvmbietmlfzoi:08514] Signal: Aborted (6)
[pkrvmbietmlfzoi:08514] Signal code:  (-6)
[pkrvmbietmlfzoi:08514] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8282a45330]
[pkrvmbietmlfzoi:08514] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8282a9eb2c]
[pkrvmbietmlfzoi:08514] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8282a4527e]
[pkrvmbietmlfzoi:08514] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8282a288ff]
[pkrvmbietmlfzoi:08514] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8282ea5ff5]
[pkrvmbietmlfzoi:08514] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8282ebb0da]
[pkrvmbietmlfzoi:08514] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8282ea5a55]
[pkrvmbietmlfzoi:08514] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8282ea5a6f]
[pkrvmbietmlfzoi:08514] [ 8] plumed_master(+0x146dd)[0x555914d766dd]
[pkrvmbietmlfzoi:08514] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8282a2a1ca]
[pkrvmbietmlfzoi:08514] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8282a2a28b]
[pkrvmbietmlfzoi:08514] [11] plumed_master(+0x15365)[0x555914d77365]
[pkrvmbietmlfzoi:08514] *** End of error message ***
</pre>
{% endraw %}
