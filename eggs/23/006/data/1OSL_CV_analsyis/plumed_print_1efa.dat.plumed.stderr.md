**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[fv-az1215-275:06090] *** Process received signal ***
[fv-az1215-275:06090] Signal: Aborted (6)
[fv-az1215-275:06090] Signal code:  (-6)
[fv-az1215-275:06090] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7e55a42520]
[fv-az1215-275:06090] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7e55a969fc]
[fv-az1215-275:06090] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7e55a42476]
[fv-az1215-275:06090] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7e55a287f3]
[fv-az1215-275:06090] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7e55ea2b9e]
[fv-az1215-275:06090] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7e55eae20c]
[fv-az1215-275:06090] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7e55eae277]
[fv-az1215-275:06090] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7e55eae52b]
[fv-az1215-275:06090] [ 8] plumed(+0x14254)[0x5559b849c254]
[fv-az1215-275:06090] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7e55a29d90]
[fv-az1215-275:06090] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7e55a29e40]
[fv-az1215-275:06090] [11] plumed(+0x14eb5)[0x5559b849ceb5]
[fv-az1215-275:06090] *** End of error message ***
</pre>
{% endraw %}
