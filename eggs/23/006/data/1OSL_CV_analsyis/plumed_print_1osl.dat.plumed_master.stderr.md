**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[fv-az1267-279:63305] *** Process received signal ***
[fv-az1267-279:63305] Signal: Aborted (6)
[fv-az1267-279:63305] Signal code:  (-6)
[fv-az1267-279:63305] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ee8445330]
[fv-az1267-279:63305] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ee849eb2c]
[fv-az1267-279:63305] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ee844527e]
[fv-az1267-279:63305] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ee84288ff]
[fv-az1267-279:63305] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ee88a5ff5]
[fv-az1267-279:63305] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ee88bb0da]
[fv-az1267-279:63305] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ee88a5a55]
[fv-az1267-279:63305] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ee88a5a6f]
[fv-az1267-279:63305] [ 8] plumed_master(+0x146dd)[0x55f7900686dd]
[fv-az1267-279:63305] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ee842a1ca]
[fv-az1267-279:63305] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ee842a28b]
[fv-az1267-279:63305] [11] plumed_master(+0x15365)[0x55f790069365]
[fv-az1267-279:63305] *** End of error message ***
</pre>
{% endraw %}
