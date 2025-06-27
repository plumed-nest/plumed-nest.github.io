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
[pkrvmbietmlfzoi:65432] *** Process received signal ***
[pkrvmbietmlfzoi:65432] Signal: Aborted (6)
[pkrvmbietmlfzoi:65432] Signal code:  (-6)
[pkrvmbietmlfzoi:65432] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa2f8c45330]
[pkrvmbietmlfzoi:65432] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa2f8c9eb2c]
[pkrvmbietmlfzoi:65432] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa2f8c4527e]
[pkrvmbietmlfzoi:65432] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2f8c288ff]
[pkrvmbietmlfzoi:65432] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa2f90a5ff5]
[pkrvmbietmlfzoi:65432] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa2f90bb0da]
[pkrvmbietmlfzoi:65432] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa2f90a5a55]
[pkrvmbietmlfzoi:65432] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa2f90a5a6f]
[pkrvmbietmlfzoi:65432] [ 8] plumed(+0x146dd)[0x559d6e60c6dd]
[pkrvmbietmlfzoi:65432] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa2f8c2a1ca]
[pkrvmbietmlfzoi:65432] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa2f8c2a28b]
[pkrvmbietmlfzoi:65432] [11] plumed(+0x15365)[0x559d6e60d365]
[pkrvmbietmlfzoi:65432] *** End of error message ***
</pre>
{% endraw %}
