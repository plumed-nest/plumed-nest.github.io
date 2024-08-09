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
[fv-az693-738:04326] *** Process received signal ***
[fv-az693-738:04326] Signal: Aborted (6)
[fv-az693-738:04326] Signal code:  (-6)
[fv-az693-738:04326] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f71a7042520]
[fv-az693-738:04326] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f71a70969fc]
[fv-az693-738:04326] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f71a7042476]
[fv-az693-738:04326] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f71a70287f3]
[fv-az693-738:04326] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f71a74a2b9e]
[fv-az693-738:04326] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f71a74ae20c]
[fv-az693-738:04326] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f71a74ae277]
[fv-az693-738:04326] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f71a74ae52b]
[fv-az693-738:04326] [ 8] plumed_master(+0x14274)[0x55b0dda46274]
[fv-az693-738:04326] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f71a7029d90]
[fv-az693-738:04326] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f71a7029e40]
[fv-az693-738:04326] [11] plumed_master(+0x14ed5)[0x55b0dda46ed5]
[fv-az693-738:04326] *** End of error message ***
</pre>
{% endraw %}
