**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:06441] *** Process received signal ***
[pkrvmpptgkbjq6m:06441] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06441] Signal code:  (-6)
[pkrvmpptgkbjq6m:06441] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe4b1845330]
[pkrvmpptgkbjq6m:06441] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe4b189eb2c]
[pkrvmpptgkbjq6m:06441] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe4b184527e]
[pkrvmpptgkbjq6m:06441] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4b18288ff]
[pkrvmpptgkbjq6m:06441] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe4b1ca5ff5]
[pkrvmpptgkbjq6m:06441] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe4b1cbb0da]
[pkrvmpptgkbjq6m:06441] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe4b1ca5a55]
[pkrvmpptgkbjq6m:06441] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe4b1ca5a6f]
[pkrvmpptgkbjq6m:06441] [ 8] plumed(+0x146dd)[0x562f16f726dd]
[pkrvmpptgkbjq6m:06441] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe4b182a1ca]
[pkrvmpptgkbjq6m:06441] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe4b182a28b]
[pkrvmpptgkbjq6m:06441] [11] plumed(+0x15365)[0x562f16f73365]
[pkrvmpptgkbjq6m:06441] *** End of error message ***
</pre>
{% endraw %}
