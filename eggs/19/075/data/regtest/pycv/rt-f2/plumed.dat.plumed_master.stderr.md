**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[pkrvmpptgkbjq6m:10889] *** Process received signal ***
[pkrvmpptgkbjq6m:10889] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10889] Signal code:  (-6)
[pkrvmpptgkbjq6m:10889] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9189a45330]
[pkrvmpptgkbjq6m:10889] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9189a9eb2c]
[pkrvmpptgkbjq6m:10889] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9189a4527e]
[pkrvmpptgkbjq6m:10889] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9189a288ff]
[pkrvmpptgkbjq6m:10889] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9189ea5ff5]
[pkrvmpptgkbjq6m:10889] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9189ebb0da]
[pkrvmpptgkbjq6m:10889] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9189ea5a55]
[pkrvmpptgkbjq6m:10889] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9189ea5a6f]
[pkrvmpptgkbjq6m:10889] [ 8] plumed_master(+0x146dd)[0x555f301536dd]
[pkrvmpptgkbjq6m:10889] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9189a2a1ca]
[pkrvmpptgkbjq6m:10889] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9189a2a28b]
[pkrvmpptgkbjq6m:10889] [11] plumed_master(+0x15365)[0x555f30154365]
[pkrvmpptgkbjq6m:10889] *** End of error message ***
</pre>
{% endraw %}
