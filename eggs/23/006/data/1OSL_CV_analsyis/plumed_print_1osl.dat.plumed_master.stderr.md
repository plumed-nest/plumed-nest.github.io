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
[pkrvmpptgkbjq6m:07985] *** Process received signal ***
[pkrvmpptgkbjq6m:07985] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07985] Signal code:  (-6)
[pkrvmpptgkbjq6m:07985] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f796f445330]
[pkrvmpptgkbjq6m:07985] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f796f49eb2c]
[pkrvmpptgkbjq6m:07985] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f796f44527e]
[pkrvmpptgkbjq6m:07985] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f796f4288ff]
[pkrvmpptgkbjq6m:07985] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f796f8a5ff5]
[pkrvmpptgkbjq6m:07985] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f796f8bb0da]
[pkrvmpptgkbjq6m:07985] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f796f8a5a55]
[pkrvmpptgkbjq6m:07985] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f796f8a5a6f]
[pkrvmpptgkbjq6m:07985] [ 8] plumed_master(+0x146dd)[0x55ea5b7c06dd]
[pkrvmpptgkbjq6m:07985] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f796f42a1ca]
[pkrvmpptgkbjq6m:07985] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f796f42a28b]
[pkrvmpptgkbjq6m:07985] [11] plumed_master(+0x15365)[0x55ea5b7c1365]
[pkrvmpptgkbjq6m:07985] *** End of error message ***
</pre>
{% endraw %}
