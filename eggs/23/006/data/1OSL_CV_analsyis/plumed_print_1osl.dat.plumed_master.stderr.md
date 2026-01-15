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
[runnervmi13qx:33495] *** Process received signal ***
[runnervmi13qx:33495] Signal: Aborted (6)
[runnervmi13qx:33495] Signal code:  (-6)
[runnervmi13qx:33495] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa443045330]
[runnervmi13qx:33495] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa44309eb2c]
[runnervmi13qx:33495] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa44304527e]
[runnervmi13qx:33495] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4430288ff]
[runnervmi13qx:33495] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4434a5ff5]
[runnervmi13qx:33495] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4434bb0da]
[runnervmi13qx:33495] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4434a5a55]
[runnervmi13qx:33495] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4434a5a6f]
[runnervmi13qx:33495] [ 8] plumed_master(+0x146dd)[0x562139ab06dd]
[runnervmi13qx:33495] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa44302a1ca]
[runnervmi13qx:33495] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa44302a28b]
[runnervmi13qx:33495] [11] plumed_master(+0x15365)[0x562139ab1365]
[runnervmi13qx:33495] *** End of error message ***
</pre>
{% endraw %}
