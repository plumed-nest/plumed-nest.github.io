**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az1215-275:07052] *** Process received signal ***
[fv-az1215-275:07052] Signal: Aborted (6)
[fv-az1215-275:07052] Signal code:  (-6)
[fv-az1215-275:07052] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f528c242520]
[fv-az1215-275:07052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f528c2969fc]
[fv-az1215-275:07052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f528c242476]
[fv-az1215-275:07052] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f528c2287f3]
[fv-az1215-275:07052] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f528c6a2b9e]
[fv-az1215-275:07052] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f528c6ae20c]
[fv-az1215-275:07052] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f528c6ae277]
[fv-az1215-275:07052] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f528c6ae52b]
[fv-az1215-275:07052] [ 8] plumed_master(+0x14254)[0x55fa5c147254]
[fv-az1215-275:07052] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f528c229d90]
[fv-az1215-275:07052] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f528c229e40]
[fv-az1215-275:07052] [11] plumed_master(+0x14eb5)[0x55fa5c147eb5]
[fv-az1215-275:07052] *** End of error message ***
</pre>
{% endraw %}
