**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[fv-az1047-397:62970] *** Process received signal ***
[fv-az1047-397:62970] Signal: Aborted (6)
[fv-az1047-397:62970] Signal code:  (-6)
[fv-az1047-397:62970] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde13e45330]
[fv-az1047-397:62970] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde13e9eb2c]
[fv-az1047-397:62970] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde13e4527e]
[fv-az1047-397:62970] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde13e288ff]
[fv-az1047-397:62970] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde142a5ff5]
[fv-az1047-397:62970] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde142bb0da]
[fv-az1047-397:62970] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde142a5a55]
[fv-az1047-397:62970] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde142a5a6f]
[fv-az1047-397:62970] [ 8] plumed_master(+0x146dd)[0x5630de5f06dd]
[fv-az1047-397:62970] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde13e2a1ca]
[fv-az1047-397:62970] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde13e2a28b]
[fv-az1047-397:62970] [11] plumed_master(+0x15365)[0x5630de5f1365]
[fv-az1047-397:62970] *** End of error message ***
</pre>
{% endraw %}
