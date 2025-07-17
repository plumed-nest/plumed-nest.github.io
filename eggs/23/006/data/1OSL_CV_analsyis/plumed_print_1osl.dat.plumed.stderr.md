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
[pkrvmq0rgcvqdmg:07427] *** Process received signal ***
[pkrvmq0rgcvqdmg:07427] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07427] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07427] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe6d7645330]
[pkrvmq0rgcvqdmg:07427] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe6d769eb2c]
[pkrvmq0rgcvqdmg:07427] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe6d764527e]
[pkrvmq0rgcvqdmg:07427] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe6d76288ff]
[pkrvmq0rgcvqdmg:07427] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe6d7aa5ff5]
[pkrvmq0rgcvqdmg:07427] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe6d7abb0da]
[pkrvmq0rgcvqdmg:07427] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe6d7aa5a55]
[pkrvmq0rgcvqdmg:07427] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe6d7aa5a6f]
[pkrvmq0rgcvqdmg:07427] [ 8] plumed(+0x146dd)[0x556313aaf6dd]
[pkrvmq0rgcvqdmg:07427] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe6d762a1ca]
[pkrvmq0rgcvqdmg:07427] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe6d762a28b]
[pkrvmq0rgcvqdmg:07427] [11] plumed(+0x15365)[0x556313ab0365]
[pkrvmq0rgcvqdmg:07427] *** End of error message ***
</pre>
{% endraw %}
