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
[pkrvmbietmlfzoi:62314] *** Process received signal ***
[pkrvmbietmlfzoi:62314] Signal: Aborted (6)
[pkrvmbietmlfzoi:62314] Signal code:  (-6)
[pkrvmbietmlfzoi:62314] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f20b4245330]
[pkrvmbietmlfzoi:62314] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f20b429eb2c]
[pkrvmbietmlfzoi:62314] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f20b424527e]
[pkrvmbietmlfzoi:62314] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f20b42288ff]
[pkrvmbietmlfzoi:62314] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f20b46a5ff5]
[pkrvmbietmlfzoi:62314] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f20b46bb0da]
[pkrvmbietmlfzoi:62314] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f20b46a5a55]
[pkrvmbietmlfzoi:62314] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f20b46a5a6f]
[pkrvmbietmlfzoi:62314] [ 8] plumed_master(+0x146dd)[0x5635b291a6dd]
[pkrvmbietmlfzoi:62314] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f20b422a1ca]
[pkrvmbietmlfzoi:62314] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f20b422a28b]
[pkrvmbietmlfzoi:62314] [11] plumed_master(+0x15365)[0x5635b291b365]
[pkrvmbietmlfzoi:62314] *** End of error message ***
</pre>
{% endraw %}
