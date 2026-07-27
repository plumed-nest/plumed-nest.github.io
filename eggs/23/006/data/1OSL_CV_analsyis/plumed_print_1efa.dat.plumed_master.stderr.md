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
[runnervmvrwv9:06725] *** Process received signal ***
[runnervmvrwv9:06725] Signal: Aborted (6)
[runnervmvrwv9:06725] Signal code:  (-6)
[runnervmvrwv9:06725] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9206e45330]
[runnervmvrwv9:06725] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9206e9eb2c]
[runnervmvrwv9:06725] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9206e4527e]
[runnervmvrwv9:06725] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9206e288ff]
[runnervmvrwv9:06725] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f92072a5ff5]
[runnervmvrwv9:06725] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f92072bb0da]
[runnervmvrwv9:06725] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f92072a5a55]
[runnervmvrwv9:06725] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f92072a5a6f]
[runnervmvrwv9:06725] [ 8] plumed_master(+0x146dd)[0x5566bcd276dd]
[runnervmvrwv9:06725] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9206e2a1ca]
[runnervmvrwv9:06725] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9206e2a28b]
[runnervmvrwv9:06725] [11] plumed_master(+0x15365)[0x5566bcd28365]
[runnervmvrwv9:06725] *** End of error message ***
</pre>
{% endraw %}
