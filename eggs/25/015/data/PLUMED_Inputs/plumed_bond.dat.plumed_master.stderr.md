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
[runnervmmklqx:04838] *** Process received signal ***
[runnervmmklqx:04838] Signal: Aborted (6)
[runnervmmklqx:04838] Signal code:  (-6)
[runnervmmklqx:04838] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6b6fc45330]
[runnervmmklqx:04838] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6b6fc9eb2c]
[runnervmmklqx:04838] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6b6fc4527e]
[runnervmmklqx:04838] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6b6fc288ff]
[runnervmmklqx:04838] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6b700a5ff5]
[runnervmmklqx:04838] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6b700bb0da]
[runnervmmklqx:04838] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6b700a5a55]
[runnervmmklqx:04838] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6b700a5a6f]
[runnervmmklqx:04838] [ 8] plumed_master(+0x146dd)[0x5651944376dd]
[runnervmmklqx:04838] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6b6fc2a1ca]
[runnervmmklqx:04838] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6b6fc2a28b]
[runnervmmklqx:04838] [11] plumed_master(+0x15365)[0x565194438365]
[runnervmmklqx:04838] *** End of error message ***
</pre>
{% endraw %}
