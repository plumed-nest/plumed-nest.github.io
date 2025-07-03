**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmbietmlfzoi:08192] *** Process received signal ***
[pkrvmbietmlfzoi:08192] Signal: Aborted (6)
[pkrvmbietmlfzoi:08192] Signal code:  (-6)
[pkrvmbietmlfzoi:08192] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62b7c45330]
[pkrvmbietmlfzoi:08192] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62b7c9eb2c]
[pkrvmbietmlfzoi:08192] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62b7c4527e]
[pkrvmbietmlfzoi:08192] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62b7c288ff]
[pkrvmbietmlfzoi:08192] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62b80a5ff5]
[pkrvmbietmlfzoi:08192] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62b80bb0da]
[pkrvmbietmlfzoi:08192] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62b80a5a55]
[pkrvmbietmlfzoi:08192] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62b80a5a6f]
[pkrvmbietmlfzoi:08192] [ 8] plumed(+0x146dd)[0x56546abd96dd]
[pkrvmbietmlfzoi:08192] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62b7c2a1ca]
[pkrvmbietmlfzoi:08192] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62b7c2a28b]
[pkrvmbietmlfzoi:08192] [11] plumed(+0x15365)[0x56546abda365]
[pkrvmbietmlfzoi:08192] *** End of error message ***
</pre>
{% endraw %}
