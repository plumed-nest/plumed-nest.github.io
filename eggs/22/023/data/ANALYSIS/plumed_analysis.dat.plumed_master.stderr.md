**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1435-511:05861] *** Process received signal ***
[fv-az1435-511:05861] Signal: Aborted (6)
[fv-az1435-511:05861] Signal code:  (-6)
[fv-az1435-511:05861] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9f03442520]
[fv-az1435-511:05861] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9f034969fc]
[fv-az1435-511:05861] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9f03442476]
[fv-az1435-511:05861] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9f034287f3]
[fv-az1435-511:05861] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9f038a2b9e]
[fv-az1435-511:05861] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9f038ae20c]
[fv-az1435-511:05861] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9f038ae277]
[fv-az1435-511:05861] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9f038ae52b]
[fv-az1435-511:05861] [ 8] plumed_master(+0x14274)[0x556ce73a4274]
[fv-az1435-511:05861] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9f03429d90]
[fv-az1435-511:05861] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9f03429e40]
[fv-az1435-511:05861] [11] plumed_master(+0x14ed5)[0x556ce73a4ed5]
[fv-az1435-511:05861] *** End of error message ***
</pre>
{% endraw %}
