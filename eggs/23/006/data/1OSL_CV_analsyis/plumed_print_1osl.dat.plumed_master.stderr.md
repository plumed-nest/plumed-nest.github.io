**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[runnervmmklqx:05745] *** Process received signal ***
[runnervmmklqx:05745] Signal: Aborted (6)
[runnervmmklqx:05745] Signal code:  (-6)
[runnervmmklqx:05745] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe21c245330]
[runnervmmklqx:05745] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe21c29eb2c]
[runnervmmklqx:05745] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe21c24527e]
[runnervmmklqx:05745] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe21c2288ff]
[runnervmmklqx:05745] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe21c6a5ff5]
[runnervmmklqx:05745] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe21c6bb0da]
[runnervmmklqx:05745] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe21c6a5a55]
[runnervmmklqx:05745] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe21c6a5a6f]
[runnervmmklqx:05745] [ 8] plumed_master(+0x146dd)[0x5604b83336dd]
[runnervmmklqx:05745] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe21c22a1ca]
[runnervmmklqx:05745] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe21c22a28b]
[runnervmmklqx:05745] [11] plumed_master(+0x15365)[0x5604b8334365]
[runnervmmklqx:05745] *** End of error message ***
</pre>
{% endraw %}
