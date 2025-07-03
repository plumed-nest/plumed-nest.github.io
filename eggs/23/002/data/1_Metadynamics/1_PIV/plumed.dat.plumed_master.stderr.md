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
[pkrvmbietmlfzoi:08463] *** Process received signal ***
[pkrvmbietmlfzoi:08463] Signal: Aborted (6)
[pkrvmbietmlfzoi:08463] Signal code:  (-6)
[pkrvmbietmlfzoi:08463] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe3b1c45330]
[pkrvmbietmlfzoi:08463] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe3b1c9eb2c]
[pkrvmbietmlfzoi:08463] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe3b1c4527e]
[pkrvmbietmlfzoi:08463] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3b1c288ff]
[pkrvmbietmlfzoi:08463] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3b20a5ff5]
[pkrvmbietmlfzoi:08463] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3b20bb0da]
[pkrvmbietmlfzoi:08463] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3b20a5a55]
[pkrvmbietmlfzoi:08463] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3b20a5a6f]
[pkrvmbietmlfzoi:08463] [ 8] plumed_master(+0x146dd)[0x556971a696dd]
[pkrvmbietmlfzoi:08463] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe3b1c2a1ca]
[pkrvmbietmlfzoi:08463] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe3b1c2a28b]
[pkrvmbietmlfzoi:08463] [11] plumed_master(+0x15365)[0x556971a6a365]
[pkrvmbietmlfzoi:08463] *** End of error message ***
</pre>
{% endraw %}
