**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[pkrvmpptgkbjq6m:10475] *** Process received signal ***
[pkrvmpptgkbjq6m:10475] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10475] Signal code:  (-6)
[pkrvmpptgkbjq6m:10475] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e90c45330]
[pkrvmpptgkbjq6m:10475] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e90c9eb2c]
[pkrvmpptgkbjq6m:10475] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e90c4527e]
[pkrvmpptgkbjq6m:10475] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e90c288ff]
[pkrvmpptgkbjq6m:10475] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e910a5ff5]
[pkrvmpptgkbjq6m:10475] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e910bb0da]
[pkrvmpptgkbjq6m:10475] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e910a5a55]
[pkrvmpptgkbjq6m:10475] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e910a5a6f]
[pkrvmpptgkbjq6m:10475] [ 8] plumed_master(+0x146dd)[0x55c2a86c16dd]
[pkrvmpptgkbjq6m:10475] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e90c2a1ca]
[pkrvmpptgkbjq6m:10475] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e90c2a28b]
[pkrvmpptgkbjq6m:10475] [11] plumed_master(+0x15365)[0x55c2a86c2365]
[pkrvmpptgkbjq6m:10475] *** End of error message ***
</pre>
{% endraw %}
