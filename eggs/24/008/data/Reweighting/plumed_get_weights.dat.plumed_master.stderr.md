**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmbietmlfzoi:63519] *** Process received signal ***
[pkrvmbietmlfzoi:63519] Signal: Aborted (6)
[pkrvmbietmlfzoi:63519] Signal code:  (-6)
[pkrvmbietmlfzoi:63519] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd26c045330]
[pkrvmbietmlfzoi:63519] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd26c09eb2c]
[pkrvmbietmlfzoi:63519] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd26c04527e]
[pkrvmbietmlfzoi:63519] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd26c0288ff]
[pkrvmbietmlfzoi:63519] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd26c4a5ff5]
[pkrvmbietmlfzoi:63519] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd26c4bb0da]
[pkrvmbietmlfzoi:63519] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd26c4a5a55]
[pkrvmbietmlfzoi:63519] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd26c4a5a6f]
[pkrvmbietmlfzoi:63519] [ 8] plumed_master(+0x146dd)[0x5639d6c1f6dd]
[pkrvmbietmlfzoi:63519] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd26c02a1ca]
[pkrvmbietmlfzoi:63519] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd26c02a28b]
[pkrvmbietmlfzoi:63519] [11] plumed_master(+0x15365)[0x5639d6c20365]
[pkrvmbietmlfzoi:63519] *** End of error message ***
</pre>
{% endraw %}
