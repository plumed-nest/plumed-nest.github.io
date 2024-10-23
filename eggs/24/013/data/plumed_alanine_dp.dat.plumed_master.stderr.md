**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[fv-az801-114:05033] *** Process received signal ***
[fv-az801-114:05033] Signal: Aborted (6)
[fv-az801-114:05033] Signal code:  (-6)
[fv-az801-114:05033] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f448e442520]
[fv-az801-114:05033] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f448e4969fc]
[fv-az801-114:05033] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f448e442476]
[fv-az801-114:05033] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f448e4287f3]
[fv-az801-114:05033] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f448e8a2b9e]
[fv-az801-114:05033] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f448e8ae20c]
[fv-az801-114:05033] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f448e8ae277]
[fv-az801-114:05033] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f448e8ae52b]
[fv-az801-114:05033] [ 8] plumed_master(+0x14254)[0x55ed53c0f254]
[fv-az801-114:05033] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f448e429d90]
[fv-az801-114:05033] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f448e429e40]
[fv-az801-114:05033] [11] plumed_master(+0x14eb5)[0x55ed53c0feb5]
[fv-az801-114:05033] *** End of error message ***
</pre>
{% endraw %}
