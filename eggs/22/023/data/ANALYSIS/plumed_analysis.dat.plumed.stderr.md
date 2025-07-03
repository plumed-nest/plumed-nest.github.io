**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmbietmlfzoi:08139] *** Process received signal ***
[pkrvmbietmlfzoi:08139] Signal: Aborted (6)
[pkrvmbietmlfzoi:08139] Signal code:  (-6)
[pkrvmbietmlfzoi:08139] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd6c6045330]
[pkrvmbietmlfzoi:08139] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd6c609eb2c]
[pkrvmbietmlfzoi:08139] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd6c604527e]
[pkrvmbietmlfzoi:08139] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6c60288ff]
[pkrvmbietmlfzoi:08139] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6c64a5ff5]
[pkrvmbietmlfzoi:08139] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6c64bb0da]
[pkrvmbietmlfzoi:08139] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6c64a5a55]
[pkrvmbietmlfzoi:08139] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6c64a5a6f]
[pkrvmbietmlfzoi:08139] [ 8] plumed(+0x146dd)[0x55d9acc426dd]
[pkrvmbietmlfzoi:08139] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd6c602a1ca]
[pkrvmbietmlfzoi:08139] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd6c602a28b]
[pkrvmbietmlfzoi:08139] [11] plumed(+0x15365)[0x55d9acc43365]
[pkrvmbietmlfzoi:08139] *** End of error message ***
</pre>
{% endraw %}
