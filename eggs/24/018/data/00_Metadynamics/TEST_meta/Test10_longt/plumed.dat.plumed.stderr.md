**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:05711] *** Process received signal ***
[pkrvmpptgkbjq6m:05711] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05711] Signal code:  (-6)
[pkrvmpptgkbjq6m:05711] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f98ca845330]
[pkrvmpptgkbjq6m:05711] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f98ca89eb2c]
[pkrvmpptgkbjq6m:05711] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f98ca84527e]
[pkrvmpptgkbjq6m:05711] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98ca8288ff]
[pkrvmpptgkbjq6m:05711] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98caca5ff5]
[pkrvmpptgkbjq6m:05711] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98cacbb0da]
[pkrvmpptgkbjq6m:05711] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98caca5a55]
[pkrvmpptgkbjq6m:05711] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98caca5a6f]
[pkrvmpptgkbjq6m:05711] [ 8] plumed(+0x146dd)[0x555ad13666dd]
[pkrvmpptgkbjq6m:05711] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f98ca82a1ca]
[pkrvmpptgkbjq6m:05711] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f98ca82a28b]
[pkrvmpptgkbjq6m:05711] [11] plumed(+0x15365)[0x555ad1367365]
[pkrvmpptgkbjq6m:05711] *** End of error message ***
</pre>
{% endraw %}
