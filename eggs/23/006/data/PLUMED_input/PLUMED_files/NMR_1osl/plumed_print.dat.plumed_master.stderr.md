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
[pkrvmq0rgcvqdmg:07498] *** Process received signal ***
[pkrvmq0rgcvqdmg:07498] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07498] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07498] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb582445330]
[pkrvmq0rgcvqdmg:07498] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb58249eb2c]
[pkrvmq0rgcvqdmg:07498] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb58244527e]
[pkrvmq0rgcvqdmg:07498] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb5824288ff]
[pkrvmq0rgcvqdmg:07498] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb5828a5ff5]
[pkrvmq0rgcvqdmg:07498] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb5828bb0da]
[pkrvmq0rgcvqdmg:07498] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb5828a5a55]
[pkrvmq0rgcvqdmg:07498] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb5828a5a6f]
[pkrvmq0rgcvqdmg:07498] [ 8] plumed_master(+0x146dd)[0x55bf15f886dd]
[pkrvmq0rgcvqdmg:07498] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb58242a1ca]
[pkrvmq0rgcvqdmg:07498] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb58242a28b]
[pkrvmq0rgcvqdmg:07498] [11] plumed_master(+0x15365)[0x55bf15f89365]
[pkrvmq0rgcvqdmg:07498] *** End of error message ***
</pre>
{% endraw %}
