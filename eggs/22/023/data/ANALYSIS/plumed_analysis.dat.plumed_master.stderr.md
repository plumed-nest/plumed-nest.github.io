**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmvrwv9:07608] *** Process received signal ***
[runnervmvrwv9:07608] Signal: Aborted (6)
[runnervmvrwv9:07608] Signal code:  (-6)
[runnervmvrwv9:07608] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f97b4a45330]
[runnervmvrwv9:07608] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f97b4a9eb2c]
[runnervmvrwv9:07608] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f97b4a4527e]
[runnervmvrwv9:07608] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97b4a288ff]
[runnervmvrwv9:07608] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97b4ea5ff5]
[runnervmvrwv9:07608] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97b4ebb0da]
[runnervmvrwv9:07608] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97b4ea5a55]
[runnervmvrwv9:07608] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97b4ea5a6f]
[runnervmvrwv9:07608] [ 8] plumed_master(+0x146dd)[0x55cd866e06dd]
[runnervmvrwv9:07608] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f97b4a2a1ca]
[runnervmvrwv9:07608] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f97b4a2a28b]
[runnervmvrwv9:07608] [11] plumed_master(+0x15365)[0x55cd866e1365]
[runnervmvrwv9:07608] *** End of error message ***
</pre>
{% endraw %}
