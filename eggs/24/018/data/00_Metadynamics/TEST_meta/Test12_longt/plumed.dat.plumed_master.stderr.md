**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:05832] *** Process received signal ***
[pkrvmpptgkbjq6m:05832] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05832] Signal code:  (-6)
[pkrvmpptgkbjq6m:05832] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24c4245330]
[pkrvmpptgkbjq6m:05832] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24c429eb2c]
[pkrvmpptgkbjq6m:05832] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24c424527e]
[pkrvmpptgkbjq6m:05832] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24c42288ff]
[pkrvmpptgkbjq6m:05832] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24c46a5ff5]
[pkrvmpptgkbjq6m:05832] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24c46bb0da]
[pkrvmpptgkbjq6m:05832] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24c46a5a55]
[pkrvmpptgkbjq6m:05832] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24c46a5a6f]
[pkrvmpptgkbjq6m:05832] [ 8] plumed_master(+0x146dd)[0x55b34f4306dd]
[pkrvmpptgkbjq6m:05832] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24c422a1ca]
[pkrvmpptgkbjq6m:05832] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24c422a28b]
[pkrvmpptgkbjq6m:05832] [11] plumed_master(+0x15365)[0x55b34f431365]
[pkrvmpptgkbjq6m:05832] *** End of error message ***
</pre>
{% endraw %}
