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
[runnervmkj6or:06706] *** Process received signal ***
[runnervmkj6or:06706] Signal: Aborted (6)
[runnervmkj6or:06706] Signal code:  (-6)
[runnervmkj6or:06706] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd3a9a45330]
[runnervmkj6or:06706] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd3a9a9eb2c]
[runnervmkj6or:06706] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd3a9a4527e]
[runnervmkj6or:06706] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3a9a288ff]
[runnervmkj6or:06706] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3a9ea5ff5]
[runnervmkj6or:06706] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3a9ebb0da]
[runnervmkj6or:06706] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3a9ea5a55]
[runnervmkj6or:06706] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3a9ea5a6f]
[runnervmkj6or:06706] [ 8] plumed_master(+0x146dd)[0x555b6dc4f6dd]
[runnervmkj6or:06706] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd3a9a2a1ca]
[runnervmkj6or:06706] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd3a9a2a28b]
[runnervmkj6or:06706] [11] plumed_master(+0x15365)[0x555b6dc50365]
[runnervmkj6or:06706] *** End of error message ***
</pre>
{% endraw %}
