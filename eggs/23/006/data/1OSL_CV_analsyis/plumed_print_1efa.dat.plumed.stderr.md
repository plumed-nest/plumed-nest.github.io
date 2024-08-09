**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[fv-az693-738:04318] *** Process received signal ***
[fv-az693-738:04318] Signal: Aborted (6)
[fv-az693-738:04318] Signal code:  (-6)
[fv-az693-738:04318] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc740442520]
[fv-az693-738:04318] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc7404969fc]
[fv-az693-738:04318] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc740442476]
[fv-az693-738:04318] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc7404287f3]
[fv-az693-738:04318] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc7408a2b9e]
[fv-az693-738:04318] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc7408ae20c]
[fv-az693-738:04318] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc7408ae277]
[fv-az693-738:04318] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc7408ae52b]
[fv-az693-738:04318] [ 8] plumed(+0x12f48)[0x564e5b49ef48]
[fv-az693-738:04318] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc740429d90]
[fv-az693-738:04318] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc740429e40]
[fv-az693-738:04318] [11] plumed(+0x131e5)[0x564e5b49f1e5]
[fv-az693-738:04318] *** End of error message ***
</pre>
{% endraw %}
