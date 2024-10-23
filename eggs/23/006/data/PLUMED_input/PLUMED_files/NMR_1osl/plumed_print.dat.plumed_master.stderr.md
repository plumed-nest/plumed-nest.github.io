**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[fv-az1215-275:06161] *** Process received signal ***
[fv-az1215-275:06161] Signal: Aborted (6)
[fv-az1215-275:06161] Signal code:  (-6)
[fv-az1215-275:06161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb394a42520]
[fv-az1215-275:06161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb394a969fc]
[fv-az1215-275:06161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb394a42476]
[fv-az1215-275:06161] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb394a287f3]
[fv-az1215-275:06161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb394ea2b9e]
[fv-az1215-275:06161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb394eae20c]
[fv-az1215-275:06161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb394eae277]
[fv-az1215-275:06161] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb394eae52b]
[fv-az1215-275:06161] [ 8] plumed_master(+0x14254)[0x560b40f45254]
[fv-az1215-275:06161] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb394a29d90]
[fv-az1215-275:06161] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb394a29e40]
[fv-az1215-275:06161] [11] plumed_master(+0x14eb5)[0x560b40f45eb5]
[fv-az1215-275:06161] *** End of error message ***
</pre>
{% endraw %}
