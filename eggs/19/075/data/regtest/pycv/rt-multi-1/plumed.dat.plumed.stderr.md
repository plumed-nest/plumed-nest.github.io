**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmpptgkbjq6m:11078] *** Process received signal ***
[pkrvmpptgkbjq6m:11078] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11078] Signal code:  (-6)
[pkrvmpptgkbjq6m:11078] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb41e45330]
[pkrvmpptgkbjq6m:11078] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb41e9eb2c]
[pkrvmpptgkbjq6m:11078] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb41e4527e]
[pkrvmpptgkbjq6m:11078] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb41e288ff]
[pkrvmpptgkbjq6m:11078] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb422a5ff5]
[pkrvmpptgkbjq6m:11078] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb422bb0da]
[pkrvmpptgkbjq6m:11078] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb422a5a55]
[pkrvmpptgkbjq6m:11078] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb422a5a6f]
[pkrvmpptgkbjq6m:11078] [ 8] plumed(+0x146dd)[0x55d67bdc36dd]
[pkrvmpptgkbjq6m:11078] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb41e2a1ca]
[pkrvmpptgkbjq6m:11078] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb41e2a28b]
[pkrvmpptgkbjq6m:11078] [11] plumed(+0x15365)[0x55d67bdc4365]
[pkrvmpptgkbjq6m:11078] *** End of error message ***
</pre>
{% endraw %}
