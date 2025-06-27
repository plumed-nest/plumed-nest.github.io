**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmbietmlfzoi:63557] *** Process received signal ***
[pkrvmbietmlfzoi:63557] Signal: Aborted (6)
[pkrvmbietmlfzoi:63557] Signal code:  (-6)
[pkrvmbietmlfzoi:63557] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8fdee45330]
[pkrvmbietmlfzoi:63557] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8fdee9eb2c]
[pkrvmbietmlfzoi:63557] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8fdee4527e]
[pkrvmbietmlfzoi:63557] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8fdee288ff]
[pkrvmbietmlfzoi:63557] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8fdf2a5ff5]
[pkrvmbietmlfzoi:63557] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8fdf2bb0da]
[pkrvmbietmlfzoi:63557] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8fdf2a5a55]
[pkrvmbietmlfzoi:63557] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8fdf2a5a6f]
[pkrvmbietmlfzoi:63557] [ 8] plumed(+0x146dd)[0x556a160636dd]
[pkrvmbietmlfzoi:63557] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8fdee2a1ca]
[pkrvmbietmlfzoi:63557] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8fdee2a28b]
[pkrvmbietmlfzoi:63557] [11] plumed(+0x15365)[0x556a16064365]
[pkrvmbietmlfzoi:63557] *** End of error message ***
</pre>
{% endraw %}
