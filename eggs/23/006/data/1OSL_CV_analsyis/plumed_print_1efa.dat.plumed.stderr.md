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
[runnervmw9dnm:08536] *** Process received signal ***
[runnervmw9dnm:08536] Signal: Aborted (6)
[runnervmw9dnm:08536] Signal code:  (-6)
[runnervmw9dnm:08536] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcbbe445330]
[runnervmw9dnm:08536] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcbbe49eb2c]
[runnervmw9dnm:08536] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcbbe44527e]
[runnervmw9dnm:08536] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcbbe4288ff]
[runnervmw9dnm:08536] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcbbe8a5ff5]
[runnervmw9dnm:08536] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcbbe8bb0da]
[runnervmw9dnm:08536] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcbbe8a5a55]
[runnervmw9dnm:08536] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcbbe8a5a6f]
[runnervmw9dnm:08536] [ 8] plumed(+0x146dd)[0x5652580f56dd]
[runnervmw9dnm:08536] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcbbe42a1ca]
[runnervmw9dnm:08536] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcbbe42a28b]
[runnervmw9dnm:08536] [11] plumed(+0x15365)[0x5652580f6365]
[runnervmw9dnm:08536] *** End of error message ***
</pre>
{% endraw %}
