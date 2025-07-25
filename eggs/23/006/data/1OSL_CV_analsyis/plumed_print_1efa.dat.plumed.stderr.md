**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[pkrvmpptgkbjq6m:07919] *** Process received signal ***
[pkrvmpptgkbjq6m:07919] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07919] Signal code:  (-6)
[pkrvmpptgkbjq6m:07919] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb897c45330]
[pkrvmpptgkbjq6m:07919] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb897c9eb2c]
[pkrvmpptgkbjq6m:07919] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb897c4527e]
[pkrvmpptgkbjq6m:07919] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb897c288ff]
[pkrvmpptgkbjq6m:07919] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8980a5ff5]
[pkrvmpptgkbjq6m:07919] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8980bb0da]
[pkrvmpptgkbjq6m:07919] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8980a5a55]
[pkrvmpptgkbjq6m:07919] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8980a5a6f]
[pkrvmpptgkbjq6m:07919] [ 8] plumed(+0x146dd)[0x56449d1496dd]
[pkrvmpptgkbjq6m:07919] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb897c2a1ca]
[pkrvmpptgkbjq6m:07919] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb897c2a28b]
[pkrvmpptgkbjq6m:07919] [11] plumed(+0x15365)[0x56449d14a365]
[pkrvmpptgkbjq6m:07919] *** End of error message ***
</pre>
{% endraw %}
