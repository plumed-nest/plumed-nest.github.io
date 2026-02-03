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
[runnervmkj6or:06152] *** Process received signal ***
[runnervmkj6or:06152] Signal: Aborted (6)
[runnervmkj6or:06152] Signal code:  (-6)
[runnervmkj6or:06152] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f43a1e45330]
[runnervmkj6or:06152] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f43a1e9eb2c]
[runnervmkj6or:06152] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f43a1e4527e]
[runnervmkj6or:06152] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f43a1e288ff]
[runnervmkj6or:06152] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f43a22a5ff5]
[runnervmkj6or:06152] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f43a22bb0da]
[runnervmkj6or:06152] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f43a22a5a55]
[runnervmkj6or:06152] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f43a22a5a6f]
[runnervmkj6or:06152] [ 8] plumed_master(+0x146dd)[0x5624a4d6f6dd]
[runnervmkj6or:06152] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f43a1e2a1ca]
[runnervmkj6or:06152] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f43a1e2a28b]
[runnervmkj6or:06152] [11] plumed_master(+0x15365)[0x5624a4d70365]
[runnervmkj6or:06152] *** End of error message ***
</pre>
{% endraw %}
