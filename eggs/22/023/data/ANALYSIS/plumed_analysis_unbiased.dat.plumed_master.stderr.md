**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1215-275:07021] *** Process received signal ***
[fv-az1215-275:07021] Signal: Aborted (6)
[fv-az1215-275:07021] Signal code:  (-6)
[fv-az1215-275:07021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7efe06e42520]
[fv-az1215-275:07021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7efe06e969fc]
[fv-az1215-275:07021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7efe06e42476]
[fv-az1215-275:07021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7efe06e287f3]
[fv-az1215-275:07021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7efe072a2b9e]
[fv-az1215-275:07021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7efe072ae20c]
[fv-az1215-275:07021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7efe072ae277]
[fv-az1215-275:07021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7efe072ae52b]
[fv-az1215-275:07021] [ 8] plumed_master(+0x14254)[0x557d55a04254]
[fv-az1215-275:07021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7efe06e29d90]
[fv-az1215-275:07021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7efe06e29e40]
[fv-az1215-275:07021] [11] plumed_master(+0x14eb5)[0x557d55a04eb5]
[fv-az1215-275:07021] *** End of error message ***
</pre>
{% endraw %}