**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervmgx7h7:05357] *** Process received signal ***
[runnervmgx7h7:05357] Signal: Aborted (6)
[runnervmgx7h7:05357] Signal code:  (-6)
[runnervmgx7h7:05357] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7d25845330]
[runnervmgx7h7:05357] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7d2589ec0c]
[runnervmgx7h7:05357] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7d2584527e]
[runnervmgx7h7:05357] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7d258288ff]
[runnervmgx7h7:05357] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7d25ca5ff5]
[runnervmgx7h7:05357] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7d25cbb0da]
[runnervmgx7h7:05357] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7d25ca5a55]
[runnervmgx7h7:05357] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7d25ca5a6f]
[runnervmgx7h7:05357] [ 8] plumed_master(+0x146dd)[0x559cc64bd6dd]
[runnervmgx7h7:05357] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7d2582a1ca]
[runnervmgx7h7:05357] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7d2582a28b]
[runnervmgx7h7:05357] [11] plumed_master(+0x15365)[0x559cc64be365]
[runnervmgx7h7:05357] *** End of error message ***
</pre>
{% endraw %}
