**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[runnervmvrwv9:06776] *** Process received signal ***
[runnervmvrwv9:06776] Signal: Aborted (6)
[runnervmvrwv9:06776] Signal code:  (-6)
[runnervmvrwv9:06776] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5cc2445330]
[runnervmvrwv9:06776] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5cc249eb2c]
[runnervmvrwv9:06776] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5cc244527e]
[runnervmvrwv9:06776] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5cc24288ff]
[runnervmvrwv9:06776] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5cc28a5ff5]
[runnervmvrwv9:06776] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5cc28bb0da]
[runnervmvrwv9:06776] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5cc28a5a55]
[runnervmvrwv9:06776] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5cc28a5a6f]
[runnervmvrwv9:06776] [ 8] plumed_master(+0x146dd)[0x5601741866dd]
[runnervmvrwv9:06776] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5cc242a1ca]
[runnervmvrwv9:06776] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5cc242a28b]
[runnervmvrwv9:06776] [11] plumed_master(+0x15365)[0x560174187365]
[runnervmvrwv9:06776] *** End of error message ***
</pre>
{% endraw %}
