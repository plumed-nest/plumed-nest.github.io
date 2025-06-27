**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[pkrvmbietmlfzoi:65448] *** Process received signal ***
[pkrvmbietmlfzoi:65448] Signal: Aborted (6)
[pkrvmbietmlfzoi:65448] Signal code:  (-6)
[pkrvmbietmlfzoi:65448] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd316445330]
[pkrvmbietmlfzoi:65448] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd31649eb2c]
[pkrvmbietmlfzoi:65448] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd31644527e]
[pkrvmbietmlfzoi:65448] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3164288ff]
[pkrvmbietmlfzoi:65448] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3168a5ff5]
[pkrvmbietmlfzoi:65448] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3168bb0da]
[pkrvmbietmlfzoi:65448] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3168a5a55]
[pkrvmbietmlfzoi:65448] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3168a5a6f]
[pkrvmbietmlfzoi:65448] [ 8] plumed_master(+0x146dd)[0x55fce6b1f6dd]
[pkrvmbietmlfzoi:65448] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd31642a1ca]
[pkrvmbietmlfzoi:65448] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd31642a28b]
[pkrvmbietmlfzoi:65448] [11] plumed_master(+0x15365)[0x55fce6b20365]
[pkrvmbietmlfzoi:65448] *** End of error message ***
</pre>
{% endraw %}
