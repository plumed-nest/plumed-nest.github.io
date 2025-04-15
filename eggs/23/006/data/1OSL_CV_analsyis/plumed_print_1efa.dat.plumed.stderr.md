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
[fv-az1047-397:62852] *** Process received signal ***
[fv-az1047-397:62852] Signal: Aborted (6)
[fv-az1047-397:62852] Signal code:  (-6)
[fv-az1047-397:62852] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8225c45330]
[fv-az1047-397:62852] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8225c9eb2c]
[fv-az1047-397:62852] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8225c4527e]
[fv-az1047-397:62852] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8225c288ff]
[fv-az1047-397:62852] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82260a5ff5]
[fv-az1047-397:62852] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82260bb0da]
[fv-az1047-397:62852] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82260a5a55]
[fv-az1047-397:62852] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82260a5a6f]
[fv-az1047-397:62852] [ 8] plumed(+0x146dd)[0x560c58d3b6dd]
[fv-az1047-397:62852] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8225c2a1ca]
[fv-az1047-397:62852] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8225c2a28b]
[fv-az1047-397:62852] [11] plumed(+0x15365)[0x560c58d3c365]
[fv-az1047-397:62852] *** End of error message ***
</pre>
{% endraw %}
