**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[pkrvmpptgkbjq6m:08488] *** Process received signal ***
[pkrvmpptgkbjq6m:08488] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08488] Signal code:  (-6)
[pkrvmpptgkbjq6m:08488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc5c0445330]
[pkrvmpptgkbjq6m:08488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc5c049eb2c]
[pkrvmpptgkbjq6m:08488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc5c044527e]
[pkrvmpptgkbjq6m:08488] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc5c04288ff]
[pkrvmpptgkbjq6m:08488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc5c08a5ff5]
[pkrvmpptgkbjq6m:08488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc5c08bb0da]
[pkrvmpptgkbjq6m:08488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc5c08a5a55]
[pkrvmpptgkbjq6m:08488] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc5c08a5a6f]
[pkrvmpptgkbjq6m:08488] [ 8] plumed_master(+0x146dd)[0x55d33a9946dd]
[pkrvmpptgkbjq6m:08488] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc5c042a1ca]
[pkrvmpptgkbjq6m:08488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc5c042a28b]
[pkrvmpptgkbjq6m:08488] [11] plumed_master(+0x15365)[0x55d33a995365]
[pkrvmpptgkbjq6m:08488] *** End of error message ***
</pre>
{% endraw %}
