**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[runnervmgx7h7:06729] *** Process received signal ***
[runnervmgx7h7:06729] Signal: Aborted (6)
[runnervmgx7h7:06729] Signal code:  (-6)
[runnervmgx7h7:06729] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19ee645330]
[runnervmgx7h7:06729] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19ee69ec0c]
[runnervmgx7h7:06729] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19ee64527e]
[runnervmgx7h7:06729] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19ee6288ff]
[runnervmgx7h7:06729] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19eeaa5ff5]
[runnervmgx7h7:06729] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19eeabb0da]
[runnervmgx7h7:06729] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19eeaa5a55]
[runnervmgx7h7:06729] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19eeaa5a6f]
[runnervmgx7h7:06729] [ 8] plumed_master(+0x146dd)[0x562a2308e6dd]
[runnervmgx7h7:06729] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19ee62a1ca]
[runnervmgx7h7:06729] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19ee62a28b]
[runnervmgx7h7:06729] [11] plumed_master(+0x15365)[0x562a2308f365]
[runnervmgx7h7:06729] *** End of error message ***
</pre>
{% endraw %}
