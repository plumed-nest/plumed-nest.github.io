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
[fv-az1215-275:06980] *** Process received signal ***
[fv-az1215-275:06980] Signal: Aborted (6)
[fv-az1215-275:06980] Signal code:  (-6)
[fv-az1215-275:06980] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6f95442520]
[fv-az1215-275:06980] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6f954969fc]
[fv-az1215-275:06980] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6f95442476]
[fv-az1215-275:06980] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6f954287f3]
[fv-az1215-275:06980] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6f958a2b9e]
[fv-az1215-275:06980] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6f958ae20c]
[fv-az1215-275:06980] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6f958ae277]
[fv-az1215-275:06980] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6f958ae52b]
[fv-az1215-275:06980] [ 8] plumed(+0x14254)[0x5591b1858254]
[fv-az1215-275:06980] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6f95429d90]
[fv-az1215-275:06980] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6f95429e40]
[fv-az1215-275:06980] [11] plumed(+0x14eb5)[0x5591b1858eb5]
[fv-az1215-275:06980] *** End of error message ***
</pre>
{% endraw %}
