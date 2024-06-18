**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1435-511:05853] *** Process received signal ***
[fv-az1435-511:05853] Signal: Aborted (6)
[fv-az1435-511:05853] Signal code:  (-6)
[fv-az1435-511:05853] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa0f6642520]
[fv-az1435-511:05853] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa0f66969fc]
[fv-az1435-511:05853] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa0f6642476]
[fv-az1435-511:05853] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa0f66287f3]
[fv-az1435-511:05853] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa0f6aa2b9e]
[fv-az1435-511:05853] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa0f6aae20c]
[fv-az1435-511:05853] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa0f6aae277]
[fv-az1435-511:05853] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa0f6aae52b]
[fv-az1435-511:05853] [ 8] plumed(+0x12f48)[0x5605f62fff48]
[fv-az1435-511:05853] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa0f6629d90]
[fv-az1435-511:05853] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa0f6629e40]
[fv-az1435-511:05853] [11] plumed(+0x131e5)[0x5605f63001e5]
[fv-az1435-511:05853] *** End of error message ***
</pre>
{% endraw %}
