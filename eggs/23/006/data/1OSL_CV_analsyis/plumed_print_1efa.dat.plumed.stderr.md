**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[fv-az1360-658:08973] *** Process received signal ***
[fv-az1360-658:08973] Signal: Aborted (6)
[fv-az1360-658:08973] Signal code:  (-6)
[fv-az1360-658:08973] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffbaa445330]
[fv-az1360-658:08973] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffbaa49eb2c]
[fv-az1360-658:08973] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffbaa44527e]
[fv-az1360-658:08973] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffbaa4288ff]
[fv-az1360-658:08973] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffbaa8a5ff5]
[fv-az1360-658:08973] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffbaa8bb0da]
[fv-az1360-658:08973] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffbaa8a5a55]
[fv-az1360-658:08973] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffbaa8a5a6f]
[fv-az1360-658:08973] [ 8] plumed(+0x146dd)[0x56351ea126dd]
[fv-az1360-658:08973] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffbaa42a1ca]
[fv-az1360-658:08973] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffbaa42a28b]
[fv-az1360-658:08973] [11] plumed(+0x15365)[0x56351ea13365]
[fv-az1360-658:08973] *** End of error message ***
</pre>
{% endraw %}
