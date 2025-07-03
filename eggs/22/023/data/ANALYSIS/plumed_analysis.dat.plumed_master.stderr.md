**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmbietmlfzoi:08155] *** Process received signal ***
[pkrvmbietmlfzoi:08155] Signal: Aborted (6)
[pkrvmbietmlfzoi:08155] Signal code:  (-6)
[pkrvmbietmlfzoi:08155] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0769a45330]
[pkrvmbietmlfzoi:08155] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0769a9eb2c]
[pkrvmbietmlfzoi:08155] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0769a4527e]
[pkrvmbietmlfzoi:08155] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0769a288ff]
[pkrvmbietmlfzoi:08155] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0769ea5ff5]
[pkrvmbietmlfzoi:08155] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0769ebb0da]
[pkrvmbietmlfzoi:08155] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0769ea5a55]
[pkrvmbietmlfzoi:08155] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0769ea5a6f]
[pkrvmbietmlfzoi:08155] [ 8] plumed_master(+0x146dd)[0x556da87c86dd]
[pkrvmbietmlfzoi:08155] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0769a2a1ca]
[pkrvmbietmlfzoi:08155] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0769a2a28b]
[pkrvmbietmlfzoi:08155] [11] plumed_master(+0x15365)[0x556da87c9365]
[pkrvmbietmlfzoi:08155] *** End of error message ***
</pre>
{% endraw %}
