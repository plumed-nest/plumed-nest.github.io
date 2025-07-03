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
[pkrvmbietmlfzoi:06237] *** Process received signal ***
[pkrvmbietmlfzoi:06237] Signal: Aborted (6)
[pkrvmbietmlfzoi:06237] Signal code:  (-6)
[pkrvmbietmlfzoi:06237] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4bdea45330]
[pkrvmbietmlfzoi:06237] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4bdea9eb2c]
[pkrvmbietmlfzoi:06237] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4bdea4527e]
[pkrvmbietmlfzoi:06237] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4bdea288ff]
[pkrvmbietmlfzoi:06237] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4bdeea5ff5]
[pkrvmbietmlfzoi:06237] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4bdeebb0da]
[pkrvmbietmlfzoi:06237] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4bdeea5a55]
[pkrvmbietmlfzoi:06237] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4bdeea5a6f]
[pkrvmbietmlfzoi:06237] [ 8] plumed(+0x146dd)[0x55e2606e86dd]
[pkrvmbietmlfzoi:06237] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4bdea2a1ca]
[pkrvmbietmlfzoi:06237] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4bdea2a28b]
[pkrvmbietmlfzoi:06237] [11] plumed(+0x15365)[0x55e2606e9365]
[pkrvmbietmlfzoi:06237] *** End of error message ***
</pre>
{% endraw %}
