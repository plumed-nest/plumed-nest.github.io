**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[pkrvmbietmlfzoi:08246] *** Process received signal ***
[pkrvmbietmlfzoi:08246] Signal: Aborted (6)
[pkrvmbietmlfzoi:08246] Signal code:  (-6)
[pkrvmbietmlfzoi:08246] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feeaec45330]
[pkrvmbietmlfzoi:08246] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feeaec9eb2c]
[pkrvmbietmlfzoi:08246] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feeaec4527e]
[pkrvmbietmlfzoi:08246] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feeaec288ff]
[pkrvmbietmlfzoi:08246] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feeaf0a5ff5]
[pkrvmbietmlfzoi:08246] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feeaf0bb0da]
[pkrvmbietmlfzoi:08246] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feeaf0a5a55]
[pkrvmbietmlfzoi:08246] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feeaf0a5a6f]
[pkrvmbietmlfzoi:08246] [ 8] plumed(+0x146dd)[0x556789bd36dd]
[pkrvmbietmlfzoi:08246] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feeaec2a1ca]
[pkrvmbietmlfzoi:08246] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feeaec2a28b]
[pkrvmbietmlfzoi:08246] [11] plumed(+0x15365)[0x556789bd4365]
[pkrvmbietmlfzoi:08246] *** End of error message ***
</pre>
{% endraw %}
