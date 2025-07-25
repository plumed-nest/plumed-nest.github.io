**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmpptgkbjq6m:10784] *** Process received signal ***
[pkrvmpptgkbjq6m:10784] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10784] Signal code:  (-6)
[pkrvmpptgkbjq6m:10784] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2fc2a45330]
[pkrvmpptgkbjq6m:10784] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2fc2a9eb2c]
[pkrvmpptgkbjq6m:10784] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2fc2a4527e]
[pkrvmpptgkbjq6m:10784] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2fc2a288ff]
[pkrvmpptgkbjq6m:10784] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2fc2ea5ff5]
[pkrvmpptgkbjq6m:10784] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2fc2ebb0da]
[pkrvmpptgkbjq6m:10784] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2fc2ea5a55]
[pkrvmpptgkbjq6m:10784] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2fc2ea5a6f]
[pkrvmpptgkbjq6m:10784] [ 8] plumed_master(+0x146dd)[0x55b50e4f26dd]
[pkrvmpptgkbjq6m:10784] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2fc2a2a1ca]
[pkrvmpptgkbjq6m:10784] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2fc2a2a28b]
[pkrvmpptgkbjq6m:10784] [11] plumed_master(+0x15365)[0x55b50e4f3365]
[pkrvmpptgkbjq6m:10784] *** End of error message ***
</pre>
{% endraw %}
