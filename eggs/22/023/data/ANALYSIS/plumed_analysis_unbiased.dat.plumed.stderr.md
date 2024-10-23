**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1215-275:07013] *** Process received signal ***
[fv-az1215-275:07013] Signal: Aborted (6)
[fv-az1215-275:07013] Signal code:  (-6)
[fv-az1215-275:07013] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbdbc442520]
[fv-az1215-275:07013] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbdbc4969fc]
[fv-az1215-275:07013] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbdbc442476]
[fv-az1215-275:07013] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbdbc4287f3]
[fv-az1215-275:07013] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbdbc8a2b9e]
[fv-az1215-275:07013] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbdbc8ae20c]
[fv-az1215-275:07013] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbdbc8ae277]
[fv-az1215-275:07013] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbdbc8ae52b]
[fv-az1215-275:07013] [ 8] plumed(+0x14254)[0x56279df01254]
[fv-az1215-275:07013] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbdbc429d90]
[fv-az1215-275:07013] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbdbc429e40]
[fv-az1215-275:07013] [11] plumed(+0x14eb5)[0x56279df01eb5]
[fv-az1215-275:07013] *** End of error message ***
</pre>
{% endraw %}
