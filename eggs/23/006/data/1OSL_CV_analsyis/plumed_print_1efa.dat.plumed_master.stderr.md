**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[fv-az1360-658:08989] *** Process received signal ***
[fv-az1360-658:08989] Signal: Aborted (6)
[fv-az1360-658:08989] Signal code:  (-6)
[fv-az1360-658:08989] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f21fc045330]
[fv-az1360-658:08989] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f21fc09eb2c]
[fv-az1360-658:08989] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f21fc04527e]
[fv-az1360-658:08989] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21fc0288ff]
[fv-az1360-658:08989] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f21fc4a5ff5]
[fv-az1360-658:08989] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f21fc4bb0da]
[fv-az1360-658:08989] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f21fc4a5a55]
[fv-az1360-658:08989] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f21fc4a5a6f]
[fv-az1360-658:08989] [ 8] plumed_master(+0x146dd)[0x55863e24f6dd]
[fv-az1360-658:08989] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f21fc02a1ca]
[fv-az1360-658:08989] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f21fc02a28b]
[fv-az1360-658:08989] [11] plumed_master(+0x15365)[0x55863e250365]
[fv-az1360-658:08989] *** End of error message ***
</pre>
{% endraw %}
