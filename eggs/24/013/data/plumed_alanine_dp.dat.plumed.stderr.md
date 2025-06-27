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
[pkrvmbietmlfzoi:62298] *** Process received signal ***
[pkrvmbietmlfzoi:62298] Signal: Aborted (6)
[pkrvmbietmlfzoi:62298] Signal code:  (-6)
[pkrvmbietmlfzoi:62298] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9886245330]
[pkrvmbietmlfzoi:62298] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f988629eb2c]
[pkrvmbietmlfzoi:62298] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f988624527e]
[pkrvmbietmlfzoi:62298] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98862288ff]
[pkrvmbietmlfzoi:62298] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98866a5ff5]
[pkrvmbietmlfzoi:62298] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98866bb0da]
[pkrvmbietmlfzoi:62298] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98866a5a55]
[pkrvmbietmlfzoi:62298] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98866a5a6f]
[pkrvmbietmlfzoi:62298] [ 8] plumed(+0x146dd)[0x558416abb6dd]
[pkrvmbietmlfzoi:62298] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f988622a1ca]
[pkrvmbietmlfzoi:62298] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f988622a28b]
[pkrvmbietmlfzoi:62298] [11] plumed(+0x15365)[0x558416abc365]
[pkrvmbietmlfzoi:62298] *** End of error message ***
</pre>
{% endraw %}
