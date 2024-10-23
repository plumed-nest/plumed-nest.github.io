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
[fv-az1215-275:06988] *** Process received signal ***
[fv-az1215-275:06988] Signal: Aborted (6)
[fv-az1215-275:06988] Signal code:  (-6)
[fv-az1215-275:06988] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff1c3a42520]
[fv-az1215-275:06988] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff1c3a969fc]
[fv-az1215-275:06988] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff1c3a42476]
[fv-az1215-275:06988] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff1c3a287f3]
[fv-az1215-275:06988] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff1c3ea2b9e]
[fv-az1215-275:06988] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff1c3eae20c]
[fv-az1215-275:06988] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff1c3eae277]
[fv-az1215-275:06988] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff1c3eae52b]
[fv-az1215-275:06988] [ 8] plumed_master(+0x14254)[0x55e4f6e28254]
[fv-az1215-275:06988] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff1c3a29d90]
[fv-az1215-275:06988] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff1c3a29e40]
[fv-az1215-275:06988] [11] plumed_master(+0x14eb5)[0x55e4f6e28eb5]
[fv-az1215-275:06988] *** End of error message ***
</pre>
{% endraw %}
