**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[fv-az1215-275:06129] *** Process received signal ***
[fv-az1215-275:06129] Signal: Aborted (6)
[fv-az1215-275:06129] Signal code:  (-6)
[fv-az1215-275:06129] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7f5b042520]
[fv-az1215-275:06129] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7f5b0969fc]
[fv-az1215-275:06129] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7f5b042476]
[fv-az1215-275:06129] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7f5b0287f3]
[fv-az1215-275:06129] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7f5b4a2b9e]
[fv-az1215-275:06129] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7f5b4ae20c]
[fv-az1215-275:06129] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7f5b4ae277]
[fv-az1215-275:06129] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7f5b4ae52b]
[fv-az1215-275:06129] [ 8] plumed_master(+0x14254)[0x55ea2625b254]
[fv-az1215-275:06129] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7f5b029d90]
[fv-az1215-275:06129] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7f5b029e40]
[fv-az1215-275:06129] [11] plumed_master(+0x14eb5)[0x55ea2625beb5]
[fv-az1215-275:06129] *** End of error message ***
</pre>
{% endraw %}
