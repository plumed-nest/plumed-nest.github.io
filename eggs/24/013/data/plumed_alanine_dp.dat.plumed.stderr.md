**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvmbietmlfzoi:06456] *** Process received signal ***
[pkrvmbietmlfzoi:06456] Signal: Aborted (6)
[pkrvmbietmlfzoi:06456] Signal code:  (-6)
[pkrvmbietmlfzoi:06456] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa5c0045330]
[pkrvmbietmlfzoi:06456] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa5c009eb2c]
[pkrvmbietmlfzoi:06456] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa5c004527e]
[pkrvmbietmlfzoi:06456] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa5c00288ff]
[pkrvmbietmlfzoi:06456] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa5c04a5ff5]
[pkrvmbietmlfzoi:06456] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa5c04bb0da]
[pkrvmbietmlfzoi:06456] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa5c04a5a55]
[pkrvmbietmlfzoi:06456] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa5c04a5a6f]
[pkrvmbietmlfzoi:06456] [ 8] plumed(+0x146dd)[0x559517c2b6dd]
[pkrvmbietmlfzoi:06456] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa5c002a1ca]
[pkrvmbietmlfzoi:06456] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa5c002a28b]
[pkrvmbietmlfzoi:06456] [11] plumed(+0x15365)[0x559517c2c365]
[pkrvmbietmlfzoi:06456] *** End of error message ***
</pre>
{% endraw %}
