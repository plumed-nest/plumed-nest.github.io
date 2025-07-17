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
[pkrvmq0rgcvqdmg:07391] *** Process received signal ***
[pkrvmq0rgcvqdmg:07391] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07391] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07391] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f630e245330]
[pkrvmq0rgcvqdmg:07391] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f630e29eb2c]
[pkrvmq0rgcvqdmg:07391] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f630e24527e]
[pkrvmq0rgcvqdmg:07391] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f630e2288ff]
[pkrvmq0rgcvqdmg:07391] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f630e6a5ff5]
[pkrvmq0rgcvqdmg:07391] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f630e6bb0da]
[pkrvmq0rgcvqdmg:07391] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f630e6a5a55]
[pkrvmq0rgcvqdmg:07391] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f630e6a5a6f]
[pkrvmq0rgcvqdmg:07391] [ 8] plumed_master(+0x146dd)[0x5578856d46dd]
[pkrvmq0rgcvqdmg:07391] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f630e22a1ca]
[pkrvmq0rgcvqdmg:07391] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f630e22a28b]
[pkrvmq0rgcvqdmg:07391] [11] plumed_master(+0x15365)[0x5578856d5365]
[pkrvmq0rgcvqdmg:07391] *** End of error message ***
</pre>
{% endraw %}
