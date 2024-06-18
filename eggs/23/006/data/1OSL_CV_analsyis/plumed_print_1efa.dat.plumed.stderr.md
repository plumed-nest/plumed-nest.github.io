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
[fv-az695-955:04415] *** Process received signal ***
[fv-az695-955:04415] Signal: Aborted (6)
[fv-az695-955:04415] Signal code:  (-6)
[fv-az695-955:04415] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f06bf442520]
[fv-az695-955:04415] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f06bf4969fc]
[fv-az695-955:04415] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f06bf442476]
[fv-az695-955:04415] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f06bf4287f3]
[fv-az695-955:04415] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f06bf8a2b9e]
[fv-az695-955:04415] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f06bf8ae20c]
[fv-az695-955:04415] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f06bf8ae277]
[fv-az695-955:04415] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f06bf8ae52b]
[fv-az695-955:04415] [ 8] plumed(+0x12f48)[0x55d3d0604f48]
[fv-az695-955:04415] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f06bf429d90]
[fv-az695-955:04415] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f06bf429e40]
[fv-az695-955:04415] [11] plumed(+0x131e5)[0x55d3d06051e5]
[fv-az695-955:04415] *** End of error message ***
</pre>
{% endraw %}
