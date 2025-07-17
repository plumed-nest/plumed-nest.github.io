**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvmq0rgcvqdmg:07008] *** Process received signal ***
[pkrvmq0rgcvqdmg:07008] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07008] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6245845330]
[pkrvmq0rgcvqdmg:07008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f624589eb2c]
[pkrvmq0rgcvqdmg:07008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f624584527e]
[pkrvmq0rgcvqdmg:07008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62458288ff]
[pkrvmq0rgcvqdmg:07008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6245ca5ff5]
[pkrvmq0rgcvqdmg:07008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6245cbb0da]
[pkrvmq0rgcvqdmg:07008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6245ca5a55]
[pkrvmq0rgcvqdmg:07008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6245ca5a6f]
[pkrvmq0rgcvqdmg:07008] [ 8] plumed_master(+0x146dd)[0x5633127726dd]
[pkrvmq0rgcvqdmg:07008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f624582a1ca]
[pkrvmq0rgcvqdmg:07008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f624582a28b]
[pkrvmq0rgcvqdmg:07008] [11] plumed_master(+0x15365)[0x563312773365]
[pkrvmq0rgcvqdmg:07008] *** End of error message ***
</pre>
{% endraw %}
