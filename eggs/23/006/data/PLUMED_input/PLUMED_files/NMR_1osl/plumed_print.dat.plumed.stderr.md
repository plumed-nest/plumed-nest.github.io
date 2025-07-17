**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[pkrvmq0rgcvqdmg:07482] *** Process received signal ***
[pkrvmq0rgcvqdmg:07482] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07482] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc55dc45330]
[pkrvmq0rgcvqdmg:07482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc55dc9eb2c]
[pkrvmq0rgcvqdmg:07482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc55dc4527e]
[pkrvmq0rgcvqdmg:07482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc55dc288ff]
[pkrvmq0rgcvqdmg:07482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc55e0a5ff5]
[pkrvmq0rgcvqdmg:07482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc55e0bb0da]
[pkrvmq0rgcvqdmg:07482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc55e0a5a55]
[pkrvmq0rgcvqdmg:07482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc55e0a5a6f]
[pkrvmq0rgcvqdmg:07482] [ 8] plumed(+0x146dd)[0x55c1acab86dd]
[pkrvmq0rgcvqdmg:07482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc55dc2a1ca]
[pkrvmq0rgcvqdmg:07482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc55dc2a28b]
[pkrvmq0rgcvqdmg:07482] [11] plumed(+0x15365)[0x55c1acab9365]
[pkrvmq0rgcvqdmg:07482] *** End of error message ***
</pre>
{% endraw %}
