**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[pkrvmpptgkbjq6m:05560] *** Process received signal ***
[pkrvmpptgkbjq6m:05560] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05560] Signal code:  (-6)
[pkrvmpptgkbjq6m:05560] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4e6445330]
[pkrvmpptgkbjq6m:05560] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4e649eb2c]
[pkrvmpptgkbjq6m:05560] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4e644527e]
[pkrvmpptgkbjq6m:05560] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4e64288ff]
[pkrvmpptgkbjq6m:05560] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4e68a5ff5]
[pkrvmpptgkbjq6m:05560] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4e68bb0da]
[pkrvmpptgkbjq6m:05560] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4e68a5a55]
[pkrvmpptgkbjq6m:05560] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4e68a5a6f]
[pkrvmpptgkbjq6m:05560] [ 8] plumed_master(+0x146dd)[0x55e1f8a5c6dd]
[pkrvmpptgkbjq6m:05560] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4e642a1ca]
[pkrvmpptgkbjq6m:05560] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4e642a28b]
[pkrvmpptgkbjq6m:05560] [11] plumed_master(+0x15365)[0x55e1f8a5d365]
[pkrvmpptgkbjq6m:05560] *** End of error message ***
</pre>
{% endraw %}
