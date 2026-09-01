**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmgx7h7:07894] *** Process received signal ***
[runnervmgx7h7:07894] Signal: Aborted (6)
[runnervmgx7h7:07894] Signal code:  (-6)
[runnervmgx7h7:07894] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe8f5045330]
[runnervmgx7h7:07894] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe8f509ec0c]
[runnervmgx7h7:07894] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe8f504527e]
[runnervmgx7h7:07894] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8f50288ff]
[runnervmgx7h7:07894] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8f54a5ff5]
[runnervmgx7h7:07894] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8f54bb0da]
[runnervmgx7h7:07894] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8f54a5a55]
[runnervmgx7h7:07894] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8f54a5a6f]
[runnervmgx7h7:07894] [ 8] plumed(+0x146dd)[0x564a944276dd]
[runnervmgx7h7:07894] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe8f502a1ca]
[runnervmgx7h7:07894] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe8f502a28b]
[runnervmgx7h7:07894] [11] plumed(+0x15365)[0x564a94428365]
[runnervmgx7h7:07894] *** End of error message ***
</pre>
{% endraw %}
