**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvmbietmlfzoi:06472] *** Process received signal ***
[pkrvmbietmlfzoi:06472] Signal: Aborted (6)
[pkrvmbietmlfzoi:06472] Signal code:  (-6)
[pkrvmbietmlfzoi:06472] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f91be845330]
[pkrvmbietmlfzoi:06472] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f91be89eb2c]
[pkrvmbietmlfzoi:06472] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f91be84527e]
[pkrvmbietmlfzoi:06472] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91be8288ff]
[pkrvmbietmlfzoi:06472] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91beca5ff5]
[pkrvmbietmlfzoi:06472] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91becbb0da]
[pkrvmbietmlfzoi:06472] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91beca5a55]
[pkrvmbietmlfzoi:06472] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91beca5a6f]
[pkrvmbietmlfzoi:06472] [ 8] plumed_master(+0x146dd)[0x56123c2f26dd]
[pkrvmbietmlfzoi:06472] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f91be82a1ca]
[pkrvmbietmlfzoi:06472] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f91be82a28b]
[pkrvmbietmlfzoi:06472] [11] plumed_master(+0x15365)[0x56123c2f3365]
[pkrvmbietmlfzoi:06472] *** End of error message ***
</pre>
{% endraw %}
