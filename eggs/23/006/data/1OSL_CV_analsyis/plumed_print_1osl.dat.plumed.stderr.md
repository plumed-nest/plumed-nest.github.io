**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[fv-az1210-136:67999] *** Process received signal ***
[fv-az1210-136:67999] Signal: Aborted (6)
[fv-az1210-136:67999] Signal code:  (-6)
[fv-az1210-136:67999] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7a52442520]
[fv-az1210-136:67999] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7a524969fc]
[fv-az1210-136:67999] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7a52442476]
[fv-az1210-136:67999] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7a524287f3]
[fv-az1210-136:67999] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f7a528a4f26]
[fv-az1210-136:67999] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f7a528b6d9c]
[fv-az1210-136:67999] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f7a528b6e07]
[fv-az1210-136:67999] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7a528b70bb]
[fv-az1210-136:67999] [ 8] plumed(+0x12f48)[0x56554a3e3f48]
[fv-az1210-136:67999] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7a52429d90]
[fv-az1210-136:67999] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7a52429e40]
[fv-az1210-136:67999] [11] plumed(+0x131e5)[0x56554a3e41e5]
[fv-az1210-136:67999] *** End of error message ***
</pre>
{% endraw %}
