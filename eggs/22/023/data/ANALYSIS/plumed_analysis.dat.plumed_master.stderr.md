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
[runnervmgx7h7:07909] *** Process received signal ***
[runnervmgx7h7:07909] Signal: Aborted (6)
[runnervmgx7h7:07909] Signal code:  (-6)
[runnervmgx7h7:07909] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e4fa45330]
[runnervmgx7h7:07909] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e4fa9ec0c]
[runnervmgx7h7:07909] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e4fa4527e]
[runnervmgx7h7:07909] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e4fa288ff]
[runnervmgx7h7:07909] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e4fea5ff5]
[runnervmgx7h7:07909] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e4febb0da]
[runnervmgx7h7:07909] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e4fea5a55]
[runnervmgx7h7:07909] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e4fea5a6f]
[runnervmgx7h7:07909] [ 8] plumed_master(+0x146dd)[0x55c16e4886dd]
[runnervmgx7h7:07909] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e4fa2a1ca]
[runnervmgx7h7:07909] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e4fa2a28b]
[runnervmgx7h7:07909] [11] plumed_master(+0x15365)[0x55c16e489365]
[runnervmgx7h7:07909] *** End of error message ***
</pre>
{% endraw %}
