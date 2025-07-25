**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[pkrvmpptgkbjq6m:07970] *** Process received signal ***
[pkrvmpptgkbjq6m:07970] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07970] Signal code:  (-6)
[pkrvmpptgkbjq6m:07970] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24dcc45330]
[pkrvmpptgkbjq6m:07970] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24dcc9eb2c]
[pkrvmpptgkbjq6m:07970] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24dcc4527e]
[pkrvmpptgkbjq6m:07970] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24dcc288ff]
[pkrvmpptgkbjq6m:07970] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24dd0a5ff5]
[pkrvmpptgkbjq6m:07970] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24dd0bb0da]
[pkrvmpptgkbjq6m:07970] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24dd0a5a55]
[pkrvmpptgkbjq6m:07970] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24dd0a5a6f]
[pkrvmpptgkbjq6m:07970] [ 8] plumed(+0x146dd)[0x5576dac3d6dd]
[pkrvmpptgkbjq6m:07970] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24dcc2a1ca]
[pkrvmpptgkbjq6m:07970] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24dcc2a28b]
[pkrvmpptgkbjq6m:07970] [11] plumed(+0x15365)[0x5576dac3e365]
[pkrvmpptgkbjq6m:07970] *** End of error message ***
</pre>
{% endraw %}
