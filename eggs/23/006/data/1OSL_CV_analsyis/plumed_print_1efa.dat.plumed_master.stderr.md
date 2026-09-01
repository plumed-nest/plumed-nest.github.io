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
[runnervmgx7h7:06627] *** Process received signal ***
[runnervmgx7h7:06627] Signal: Aborted (6)
[runnervmgx7h7:06627] Signal code:  (-6)
[runnervmgx7h7:06627] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a61e45330]
[runnervmgx7h7:06627] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a61e9ec0c]
[runnervmgx7h7:06627] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a61e4527e]
[runnervmgx7h7:06627] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a61e288ff]
[runnervmgx7h7:06627] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a622a5ff5]
[runnervmgx7h7:06627] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a622bb0da]
[runnervmgx7h7:06627] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a622a5a55]
[runnervmgx7h7:06627] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a622a5a6f]
[runnervmgx7h7:06627] [ 8] plumed_master(+0x146dd)[0x55bf361126dd]
[runnervmgx7h7:06627] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a61e2a1ca]
[runnervmgx7h7:06627] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a61e2a28b]
[runnervmgx7h7:06627] [11] plumed_master(+0x15365)[0x55bf36113365]
[runnervmgx7h7:06627] *** End of error message ***
</pre>
{% endraw %}
