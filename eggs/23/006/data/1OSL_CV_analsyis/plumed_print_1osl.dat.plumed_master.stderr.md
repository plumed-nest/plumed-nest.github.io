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
[pkrvmxyh4eaekms:07164] *** Process received signal ***
[pkrvmxyh4eaekms:07164] Signal: Aborted (6)
[pkrvmxyh4eaekms:07164] Signal code:  (-6)
[pkrvmxyh4eaekms:07164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f08e45330]
[pkrvmxyh4eaekms:07164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f08e9eb2c]
[pkrvmxyh4eaekms:07164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f08e4527e]
[pkrvmxyh4eaekms:07164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f08e288ff]
[pkrvmxyh4eaekms:07164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f092a5ff5]
[pkrvmxyh4eaekms:07164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f092bb0da]
[pkrvmxyh4eaekms:07164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f092a5a55]
[pkrvmxyh4eaekms:07164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f092a5a6f]
[pkrvmxyh4eaekms:07164] [ 8] plumed_master(+0x146dd)[0x55d387af16dd]
[pkrvmxyh4eaekms:07164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f08e2a1ca]
[pkrvmxyh4eaekms:07164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f08e2a28b]
[pkrvmxyh4eaekms:07164] [11] plumed_master(+0x15365)[0x55d387af2365]
[pkrvmxyh4eaekms:07164] *** End of error message ***
</pre>
{% endraw %}
