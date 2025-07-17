**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmq0rgcvqdmg:09026] *** Process received signal ***
[pkrvmq0rgcvqdmg:09026] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09026] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09026] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff90d645330]
[pkrvmq0rgcvqdmg:09026] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff90d69eb2c]
[pkrvmq0rgcvqdmg:09026] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff90d64527e]
[pkrvmq0rgcvqdmg:09026] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff90d6288ff]
[pkrvmq0rgcvqdmg:09026] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff90daa5ff5]
[pkrvmq0rgcvqdmg:09026] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff90dabb0da]
[pkrvmq0rgcvqdmg:09026] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff90daa5a55]
[pkrvmq0rgcvqdmg:09026] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff90daa5a6f]
[pkrvmq0rgcvqdmg:09026] [ 8] plumed(+0x146dd)[0x559e627c26dd]
[pkrvmq0rgcvqdmg:09026] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff90d62a1ca]
[pkrvmq0rgcvqdmg:09026] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff90d62a28b]
[pkrvmq0rgcvqdmg:09026] [11] plumed(+0x15365)[0x559e627c3365]
[pkrvmq0rgcvqdmg:09026] *** End of error message ***
</pre>
{% endraw %}
