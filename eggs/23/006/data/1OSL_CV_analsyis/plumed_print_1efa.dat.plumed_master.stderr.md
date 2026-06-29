**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[runnervmmklqx:05694] *** Process received signal ***
[runnervmmklqx:05694] Signal: Aborted (6)
[runnervmmklqx:05694] Signal code:  (-6)
[runnervmmklqx:05694] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f185c645330]
[runnervmmklqx:05694] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f185c69eb2c]
[runnervmmklqx:05694] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f185c64527e]
[runnervmmklqx:05694] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f185c6288ff]
[runnervmmklqx:05694] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f185caa5ff5]
[runnervmmklqx:05694] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f185cabb0da]
[runnervmmklqx:05694] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f185caa5a55]
[runnervmmklqx:05694] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f185caa5a6f]
[runnervmmklqx:05694] [ 8] plumed_master(+0x146dd)[0x55bf572336dd]
[runnervmmklqx:05694] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f185c62a1ca]
[runnervmmklqx:05694] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f185c62a28b]
[runnervmmklqx:05694] [11] plumed_master(+0x15365)[0x55bf57234365]
[runnervmmklqx:05694] *** End of error message ***
</pre>
{% endraw %}
