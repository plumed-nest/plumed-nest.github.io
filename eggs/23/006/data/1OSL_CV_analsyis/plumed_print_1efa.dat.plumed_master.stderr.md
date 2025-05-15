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
[pkrvmberfyhpb9w:07601] *** Process received signal ***
[pkrvmberfyhpb9w:07601] Signal: Aborted (6)
[pkrvmberfyhpb9w:07601] Signal code:  (-6)
[pkrvmberfyhpb9w:07601] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0850245330]
[pkrvmberfyhpb9w:07601] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f085029eb2c]
[pkrvmberfyhpb9w:07601] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f085024527e]
[pkrvmberfyhpb9w:07601] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f08502288ff]
[pkrvmberfyhpb9w:07601] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f08506a5ff5]
[pkrvmberfyhpb9w:07601] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f08506bb0da]
[pkrvmberfyhpb9w:07601] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f08506a5a55]
[pkrvmberfyhpb9w:07601] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f08506a5a6f]
[pkrvmberfyhpb9w:07601] [ 8] plumed_master(+0x146dd)[0x55c4d97fa6dd]
[pkrvmberfyhpb9w:07601] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f085022a1ca]
[pkrvmberfyhpb9w:07601] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f085022a28b]
[pkrvmberfyhpb9w:07601] [11] plumed_master(+0x15365)[0x55c4d97fb365]
[pkrvmberfyhpb9w:07601] *** End of error message ***
</pre>
{% endraw %}
