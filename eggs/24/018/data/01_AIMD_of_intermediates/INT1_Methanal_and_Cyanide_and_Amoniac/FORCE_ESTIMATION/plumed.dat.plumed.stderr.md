**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:06183] *** Process received signal ***
[pkrvmpptgkbjq6m:06183] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06183] Signal code:  (-6)
[pkrvmpptgkbjq6m:06183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f732a645330]
[pkrvmpptgkbjq6m:06183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f732a69eb2c]
[pkrvmpptgkbjq6m:06183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f732a64527e]
[pkrvmpptgkbjq6m:06183] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f732a6288ff]
[pkrvmpptgkbjq6m:06183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f732aaa5ff5]
[pkrvmpptgkbjq6m:06183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f732aabb0da]
[pkrvmpptgkbjq6m:06183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f732aaa5a55]
[pkrvmpptgkbjq6m:06183] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f732aaa5a6f]
[pkrvmpptgkbjq6m:06183] [ 8] plumed(+0x146dd)[0x560da92846dd]
[pkrvmpptgkbjq6m:06183] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f732a62a1ca]
[pkrvmpptgkbjq6m:06183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f732a62a28b]
[pkrvmpptgkbjq6m:06183] [11] plumed(+0x15365)[0x560da9285365]
[pkrvmpptgkbjq6m:06183] *** End of error message ***
</pre>
{% endraw %}
