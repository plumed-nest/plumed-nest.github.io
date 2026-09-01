**Project ID:** [plumID:26.013]({{ '/' | absolute_url }}eggs/26/013/)  
Stderr for source:  3PA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../em_ww.pdb
[runnervmgx7h7:04058] *** Process received signal ***
[runnervmgx7h7:04058] Signal: Aborted (6)
[runnervmgx7h7:04058] Signal code:  (-6)
[runnervmgx7h7:04058] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe0d5445330]
[runnervmgx7h7:04058] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe0d549ec0c]
[runnervmgx7h7:04058] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe0d544527e]
[runnervmgx7h7:04058] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0d54288ff]
[runnervmgx7h7:04058] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe0d58a5ff5]
[runnervmgx7h7:04058] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe0d58bb0da]
[runnervmgx7h7:04058] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe0d58a5a55]
[runnervmgx7h7:04058] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe0d58a5a6f]
[runnervmgx7h7:04058] [ 8] plumed(+0x146dd)[0x55c7eb1376dd]
[runnervmgx7h7:04058] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe0d542a1ca]
[runnervmgx7h7:04058] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe0d542a28b]
[runnervmgx7h7:04058] [11] plumed(+0x15365)[0x55c7eb138365]
[runnervmgx7h7:04058] *** End of error message ***
</pre>
{% endraw %}
