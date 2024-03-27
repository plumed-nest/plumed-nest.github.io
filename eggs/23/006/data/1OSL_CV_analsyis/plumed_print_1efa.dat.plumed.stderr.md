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
[fv-az1210-136:67968] *** Process received signal ***
[fv-az1210-136:67968] Signal: Aborted (6)
[fv-az1210-136:67968] Signal code:  (-6)
[fv-az1210-136:67968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4fae642520]
[fv-az1210-136:67968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4fae6969fc]
[fv-az1210-136:67968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4fae642476]
[fv-az1210-136:67968] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4fae6287f3]
[fv-az1210-136:67968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f4faeaa4f26]
[fv-az1210-136:67968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f4faeab6d9c]
[fv-az1210-136:67968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f4faeab6e07]
[fv-az1210-136:67968] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4faeab70bb]
[fv-az1210-136:67968] [ 8] plumed(+0x12f48)[0x562114ae3f48]
[fv-az1210-136:67968] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4fae629d90]
[fv-az1210-136:67968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4fae629e40]
[fv-az1210-136:67968] [11] plumed(+0x131e5)[0x562114ae41e5]
[fv-az1210-136:67968] *** End of error message ***
</pre>
{% endraw %}
