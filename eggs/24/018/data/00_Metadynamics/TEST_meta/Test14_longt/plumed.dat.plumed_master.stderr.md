**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:05939] *** Process received signal ***
[pkrvmpptgkbjq6m:05939] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05939] Signal code:  (-6)
[pkrvmpptgkbjq6m:05939] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f263f045330]
[pkrvmpptgkbjq6m:05939] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f263f09eb2c]
[pkrvmpptgkbjq6m:05939] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f263f04527e]
[pkrvmpptgkbjq6m:05939] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f263f0288ff]
[pkrvmpptgkbjq6m:05939] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f263f4a5ff5]
[pkrvmpptgkbjq6m:05939] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f263f4bb0da]
[pkrvmpptgkbjq6m:05939] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f263f4a5a55]
[pkrvmpptgkbjq6m:05939] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f263f4a5a6f]
[pkrvmpptgkbjq6m:05939] [ 8] plumed_master(+0x146dd)[0x5613881346dd]
[pkrvmpptgkbjq6m:05939] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f263f02a1ca]
[pkrvmpptgkbjq6m:05939] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f263f02a28b]
[pkrvmpptgkbjq6m:05939] [11] plumed_master(+0x15365)[0x561388135365]
[pkrvmpptgkbjq6m:05939] *** End of error message ***
</pre>
{% endraw %}
