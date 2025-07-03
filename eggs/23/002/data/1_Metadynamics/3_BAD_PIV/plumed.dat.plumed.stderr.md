**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:08550] *** Process received signal ***
[pkrvmbietmlfzoi:08550] Signal: Aborted (6)
[pkrvmbietmlfzoi:08550] Signal code:  (-6)
[pkrvmbietmlfzoi:08550] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f85245330]
[pkrvmbietmlfzoi:08550] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f8529eb2c]
[pkrvmbietmlfzoi:08550] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f8524527e]
[pkrvmbietmlfzoi:08550] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f852288ff]
[pkrvmbietmlfzoi:08550] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f856a5ff5]
[pkrvmbietmlfzoi:08550] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f856bb0da]
[pkrvmbietmlfzoi:08550] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f856a5a55]
[pkrvmbietmlfzoi:08550] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f856a5a6f]
[pkrvmbietmlfzoi:08550] [ 8] plumed(+0x146dd)[0x558a63c526dd]
[pkrvmbietmlfzoi:08550] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f8522a1ca]
[pkrvmbietmlfzoi:08550] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f8522a28b]
[pkrvmbietmlfzoi:08550] [11] plumed(+0x15365)[0x558a63c53365]
[pkrvmbietmlfzoi:08550] *** End of error message ***
</pre>
{% endraw %}
