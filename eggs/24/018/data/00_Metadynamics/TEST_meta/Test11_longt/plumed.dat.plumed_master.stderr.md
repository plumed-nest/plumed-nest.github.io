**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:05778] *** Process received signal ***
[pkrvmpptgkbjq6m:05778] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05778] Signal code:  (-6)
[pkrvmpptgkbjq6m:05778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb93645330]
[pkrvmpptgkbjq6m:05778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb9369eb2c]
[pkrvmpptgkbjq6m:05778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb9364527e]
[pkrvmpptgkbjq6m:05778] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb936288ff]
[pkrvmpptgkbjq6m:05778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb93aa5ff5]
[pkrvmpptgkbjq6m:05778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb93abb0da]
[pkrvmpptgkbjq6m:05778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb93aa5a55]
[pkrvmpptgkbjq6m:05778] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb93aa5a6f]
[pkrvmpptgkbjq6m:05778] [ 8] plumed_master(+0x146dd)[0x555b56a266dd]
[pkrvmpptgkbjq6m:05778] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb9362a1ca]
[pkrvmpptgkbjq6m:05778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb9362a28b]
[pkrvmpptgkbjq6m:05778] [11] plumed_master(+0x15365)[0x555b56a27365]
[pkrvmpptgkbjq6m:05778] *** End of error message ***
</pre>
{% endraw %}
