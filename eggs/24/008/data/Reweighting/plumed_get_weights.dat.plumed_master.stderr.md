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
[pkrvmbietmlfzoi:06199] *** Process received signal ***
[pkrvmbietmlfzoi:06199] Signal: Aborted (6)
[pkrvmbietmlfzoi:06199] Signal code:  (-6)
[pkrvmbietmlfzoi:06199] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc5e1445330]
[pkrvmbietmlfzoi:06199] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc5e149eb2c]
[pkrvmbietmlfzoi:06199] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc5e144527e]
[pkrvmbietmlfzoi:06199] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc5e14288ff]
[pkrvmbietmlfzoi:06199] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc5e18a5ff5]
[pkrvmbietmlfzoi:06199] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc5e18bb0da]
[pkrvmbietmlfzoi:06199] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc5e18a5a55]
[pkrvmbietmlfzoi:06199] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc5e18a5a6f]
[pkrvmbietmlfzoi:06199] [ 8] plumed_master(+0x146dd)[0x56361d6db6dd]
[pkrvmbietmlfzoi:06199] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc5e142a1ca]
[pkrvmbietmlfzoi:06199] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc5e142a28b]
[pkrvmbietmlfzoi:06199] [11] plumed_master(+0x15365)[0x56361d6dc365]
[pkrvmbietmlfzoi:06199] *** End of error message ***
</pre>
{% endraw %}
