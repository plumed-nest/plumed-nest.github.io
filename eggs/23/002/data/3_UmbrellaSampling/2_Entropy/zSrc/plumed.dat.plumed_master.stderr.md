**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:63352] *** Process received signal ***
[pkrvmbietmlfzoi:63352] Signal: Aborted (6)
[pkrvmbietmlfzoi:63352] Signal code:  (-6)
[pkrvmbietmlfzoi:63352] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4fd245330]
[pkrvmbietmlfzoi:63352] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4fd29eb2c]
[pkrvmbietmlfzoi:63352] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4fd24527e]
[pkrvmbietmlfzoi:63352] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4fd2288ff]
[pkrvmbietmlfzoi:63352] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4fd6a5ff5]
[pkrvmbietmlfzoi:63352] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4fd6bb0da]
[pkrvmbietmlfzoi:63352] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4fd6a5a55]
[pkrvmbietmlfzoi:63352] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4fd6a5a6f]
[pkrvmbietmlfzoi:63352] [ 8] plumed_master(+0x146dd)[0x55589841d6dd]
[pkrvmbietmlfzoi:63352] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4fd22a1ca]
[pkrvmbietmlfzoi:63352] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4fd22a28b]
[pkrvmbietmlfzoi:63352] [11] plumed_master(+0x15365)[0x55589841e365]
[pkrvmbietmlfzoi:63352] *** End of error message ***
</pre>
{% endraw %}
