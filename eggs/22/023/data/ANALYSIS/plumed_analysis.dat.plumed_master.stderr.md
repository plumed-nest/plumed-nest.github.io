**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmq0rgcvqdmg:08988] *** Process received signal ***
[pkrvmq0rgcvqdmg:08988] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08988] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08988] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a4f445330]
[pkrvmq0rgcvqdmg:08988] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a4f49eb2c]
[pkrvmq0rgcvqdmg:08988] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a4f44527e]
[pkrvmq0rgcvqdmg:08988] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a4f4288ff]
[pkrvmq0rgcvqdmg:08988] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a4f8a5ff5]
[pkrvmq0rgcvqdmg:08988] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a4f8bb0da]
[pkrvmq0rgcvqdmg:08988] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a4f8a5a55]
[pkrvmq0rgcvqdmg:08988] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a4f8a5a6f]
[pkrvmq0rgcvqdmg:08988] [ 8] plumed_master(+0x146dd)[0x5580dfd4f6dd]
[pkrvmq0rgcvqdmg:08988] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a4f42a1ca]
[pkrvmq0rgcvqdmg:08988] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a4f42a28b]
[pkrvmq0rgcvqdmg:08988] [11] plumed_master(+0x15365)[0x5580dfd50365]
[pkrvmq0rgcvqdmg:08988] *** End of error message ***
</pre>
{% endraw %}
