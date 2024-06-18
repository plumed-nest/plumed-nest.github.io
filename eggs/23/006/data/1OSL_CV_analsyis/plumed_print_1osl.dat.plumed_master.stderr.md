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
[fv-az695-955:04455] *** Process received signal ***
[fv-az695-955:04455] Signal: Aborted (6)
[fv-az695-955:04455] Signal code:  (-6)
[fv-az695-955:04455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9451242520]
[fv-az695-955:04455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f94512969fc]
[fv-az695-955:04455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9451242476]
[fv-az695-955:04455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f94512287f3]
[fv-az695-955:04455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f94516a2b9e]
[fv-az695-955:04455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f94516ae20c]
[fv-az695-955:04455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f94516ae277]
[fv-az695-955:04455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f94516ae52b]
[fv-az695-955:04455] [ 8] plumed_master(+0x14274)[0x564058c53274]
[fv-az695-955:04455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9451229d90]
[fv-az695-955:04455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9451229e40]
[fv-az695-955:04455] [11] plumed_master(+0x14ed5)[0x564058c53ed5]
[fv-az695-955:04455] *** End of error message ***
</pre>
{% endraw %}
