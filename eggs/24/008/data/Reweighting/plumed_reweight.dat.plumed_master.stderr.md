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
[pkrvmbietmlfzoi:06253] *** Process received signal ***
[pkrvmbietmlfzoi:06253] Signal: Aborted (6)
[pkrvmbietmlfzoi:06253] Signal code:  (-6)
[pkrvmbietmlfzoi:06253] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc0ae45330]
[pkrvmbietmlfzoi:06253] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc0ae9eb2c]
[pkrvmbietmlfzoi:06253] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc0ae4527e]
[pkrvmbietmlfzoi:06253] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc0ae288ff]
[pkrvmbietmlfzoi:06253] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc0b2a5ff5]
[pkrvmbietmlfzoi:06253] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc0b2bb0da]
[pkrvmbietmlfzoi:06253] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc0b2a5a55]
[pkrvmbietmlfzoi:06253] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc0b2a5a6f]
[pkrvmbietmlfzoi:06253] [ 8] plumed_master(+0x146dd)[0x564553fd06dd]
[pkrvmbietmlfzoi:06253] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc0ae2a1ca]
[pkrvmbietmlfzoi:06253] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc0ae2a28b]
[pkrvmbietmlfzoi:06253] [11] plumed_master(+0x15365)[0x564553fd1365]
[pkrvmbietmlfzoi:06253] *** End of error message ***
</pre>
{% endraw %}
