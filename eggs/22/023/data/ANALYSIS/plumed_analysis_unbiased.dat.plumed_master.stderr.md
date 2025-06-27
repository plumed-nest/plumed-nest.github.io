**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmbietmlfzoi:65395] *** Process received signal ***
[pkrvmbietmlfzoi:65395] Signal: Aborted (6)
[pkrvmbietmlfzoi:65395] Signal code:  (-6)
[pkrvmbietmlfzoi:65395] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa8b2845330]
[pkrvmbietmlfzoi:65395] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa8b289eb2c]
[pkrvmbietmlfzoi:65395] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa8b284527e]
[pkrvmbietmlfzoi:65395] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa8b28288ff]
[pkrvmbietmlfzoi:65395] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8b2ca5ff5]
[pkrvmbietmlfzoi:65395] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8b2cbb0da]
[pkrvmbietmlfzoi:65395] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8b2ca5a55]
[pkrvmbietmlfzoi:65395] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8b2ca5a6f]
[pkrvmbietmlfzoi:65395] [ 8] plumed_master(+0x146dd)[0x55b49fc4a6dd]
[pkrvmbietmlfzoi:65395] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa8b282a1ca]
[pkrvmbietmlfzoi:65395] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa8b282a28b]
[pkrvmbietmlfzoi:65395] [11] plumed_master(+0x15365)[0x55b49fc4b365]
[pkrvmbietmlfzoi:65395] *** End of error message ***
</pre>
{% endraw %}
