**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/ORIGINAL_meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:05658] *** Process received signal ***
[pkrvmpptgkbjq6m:05658] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05658] Signal code:  (-6)
[pkrvmpptgkbjq6m:05658] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a3d245330]
[pkrvmpptgkbjq6m:05658] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a3d29eb2c]
[pkrvmpptgkbjq6m:05658] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a3d24527e]
[pkrvmpptgkbjq6m:05658] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a3d2288ff]
[pkrvmpptgkbjq6m:05658] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a3d6a5ff5]
[pkrvmpptgkbjq6m:05658] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a3d6bb0da]
[pkrvmpptgkbjq6m:05658] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a3d6a5a55]
[pkrvmpptgkbjq6m:05658] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a3d6a5a6f]
[pkrvmpptgkbjq6m:05658] [ 8] plumed(+0x146dd)[0x55be346cb6dd]
[pkrvmpptgkbjq6m:05658] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a3d22a1ca]
[pkrvmpptgkbjq6m:05658] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a3d22a28b]
[pkrvmpptgkbjq6m:05658] [11] plumed(+0x15365)[0x55be346cc365]
[pkrvmpptgkbjq6m:05658] *** End of error message ***
</pre>
{% endraw %}
