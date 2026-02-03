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
[runnervmkj6or:06206] *** Process received signal ***
[runnervmkj6or:06206] Signal: Aborted (6)
[runnervmkj6or:06206] Signal code:  (-6)
[runnervmkj6or:06206] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4739045330]
[runnervmkj6or:06206] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f473909eb2c]
[runnervmkj6or:06206] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f473904527e]
[runnervmkj6or:06206] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47390288ff]
[runnervmkj6or:06206] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47394a5ff5]
[runnervmkj6or:06206] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47394bb0da]
[runnervmkj6or:06206] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47394a5a55]
[runnervmkj6or:06206] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47394a5a6f]
[runnervmkj6or:06206] [ 8] plumed_master(+0x146dd)[0x56266f4216dd]
[runnervmkj6or:06206] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f473902a1ca]
[runnervmkj6or:06206] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f473902a28b]
[runnervmkj6or:06206] [11] plumed_master(+0x15365)[0x56266f422365]
[runnervmkj6or:06206] *** End of error message ***
</pre>
{% endraw %}
