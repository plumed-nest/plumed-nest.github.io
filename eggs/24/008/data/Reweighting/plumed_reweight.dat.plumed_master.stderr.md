**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmbietmlfzoi:63573] *** Process received signal ***
[pkrvmbietmlfzoi:63573] Signal: Aborted (6)
[pkrvmbietmlfzoi:63573] Signal code:  (-6)
[pkrvmbietmlfzoi:63573] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5182c45330]
[pkrvmbietmlfzoi:63573] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5182c9eb2c]
[pkrvmbietmlfzoi:63573] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5182c4527e]
[pkrvmbietmlfzoi:63573] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5182c288ff]
[pkrvmbietmlfzoi:63573] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51830a5ff5]
[pkrvmbietmlfzoi:63573] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51830bb0da]
[pkrvmbietmlfzoi:63573] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51830a5a55]
[pkrvmbietmlfzoi:63573] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51830a5a6f]
[pkrvmbietmlfzoi:63573] [ 8] plumed_master(+0x146dd)[0x55c6bef796dd]
[pkrvmbietmlfzoi:63573] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5182c2a1ca]
[pkrvmbietmlfzoi:63573] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5182c2a28b]
[pkrvmbietmlfzoi:63573] [11] plumed_master(+0x15365)[0x55c6bef7a365]
[pkrvmbietmlfzoi:63573] *** End of error message ***
</pre>
{% endraw %}
