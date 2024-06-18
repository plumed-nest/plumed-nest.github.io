**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[fv-az695-955:04423] *** Process received signal ***
[fv-az695-955:04423] Signal: Aborted (6)
[fv-az695-955:04423] Signal code:  (-6)
[fv-az695-955:04423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4224a42520]
[fv-az695-955:04423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4224a969fc]
[fv-az695-955:04423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4224a42476]
[fv-az695-955:04423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4224a287f3]
[fv-az695-955:04423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f4224ea2b9e]
[fv-az695-955:04423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f4224eae20c]
[fv-az695-955:04423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f4224eae277]
[fv-az695-955:04423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4224eae52b]
[fv-az695-955:04423] [ 8] plumed_master(+0x14274)[0x55605b6be274]
[fv-az695-955:04423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4224a29d90]
[fv-az695-955:04423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4224a29e40]
[fv-az695-955:04423] [11] plumed_master(+0x14ed5)[0x55605b6beed5]
[fv-az695-955:04423] *** End of error message ***
</pre>
{% endraw %}
