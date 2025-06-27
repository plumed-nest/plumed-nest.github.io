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
[pkrvmbietmlfzoi:63130] *** Process received signal ***
[pkrvmbietmlfzoi:63130] Signal: Aborted (6)
[pkrvmbietmlfzoi:63130] Signal code:  (-6)
[pkrvmbietmlfzoi:63130] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f73a2e45330]
[pkrvmbietmlfzoi:63130] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f73a2e9eb2c]
[pkrvmbietmlfzoi:63130] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f73a2e4527e]
[pkrvmbietmlfzoi:63130] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f73a2e288ff]
[pkrvmbietmlfzoi:63130] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73a32a5ff5]
[pkrvmbietmlfzoi:63130] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73a32bb0da]
[pkrvmbietmlfzoi:63130] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73a32a5a55]
[pkrvmbietmlfzoi:63130] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73a32a5a6f]
[pkrvmbietmlfzoi:63130] [ 8] plumed(+0x146dd)[0x55657badd6dd]
[pkrvmbietmlfzoi:63130] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f73a2e2a1ca]
[pkrvmbietmlfzoi:63130] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f73a2e2a28b]
[pkrvmbietmlfzoi:63130] [11] plumed(+0x15365)[0x55657bade365]
[pkrvmbietmlfzoi:63130] *** End of error message ***
</pre>
{% endraw %}
