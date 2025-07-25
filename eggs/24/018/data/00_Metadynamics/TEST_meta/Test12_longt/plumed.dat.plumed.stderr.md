**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:05816] *** Process received signal ***
[pkrvmpptgkbjq6m:05816] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05816] Signal code:  (-6)
[pkrvmpptgkbjq6m:05816] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff17ec45330]
[pkrvmpptgkbjq6m:05816] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff17ec9eb2c]
[pkrvmpptgkbjq6m:05816] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff17ec4527e]
[pkrvmpptgkbjq6m:05816] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff17ec288ff]
[pkrvmpptgkbjq6m:05816] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff17f0a5ff5]
[pkrvmpptgkbjq6m:05816] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff17f0bb0da]
[pkrvmpptgkbjq6m:05816] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff17f0a5a55]
[pkrvmpptgkbjq6m:05816] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff17f0a5a6f]
[pkrvmpptgkbjq6m:05816] [ 8] plumed(+0x146dd)[0x5638b54006dd]
[pkrvmpptgkbjq6m:05816] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff17ec2a1ca]
[pkrvmpptgkbjq6m:05816] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff17ec2a28b]
[pkrvmpptgkbjq6m:05816] [11] plumed(+0x15365)[0x5638b5401365]
[pkrvmpptgkbjq6m:05816] *** End of error message ***
</pre>
{% endraw %}
