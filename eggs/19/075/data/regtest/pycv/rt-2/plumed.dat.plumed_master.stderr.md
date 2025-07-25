**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmpptgkbjq6m:10734] *** Process received signal ***
[pkrvmpptgkbjq6m:10734] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10734] Signal code:  (-6)
[pkrvmpptgkbjq6m:10734] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c50c45330]
[pkrvmpptgkbjq6m:10734] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c50c9eb2c]
[pkrvmpptgkbjq6m:10734] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c50c4527e]
[pkrvmpptgkbjq6m:10734] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c50c288ff]
[pkrvmpptgkbjq6m:10734] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c510a5ff5]
[pkrvmpptgkbjq6m:10734] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c510bb0da]
[pkrvmpptgkbjq6m:10734] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c510a5a55]
[pkrvmpptgkbjq6m:10734] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c510a5a6f]
[pkrvmpptgkbjq6m:10734] [ 8] plumed_master(+0x146dd)[0x5571428556dd]
[pkrvmpptgkbjq6m:10734] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c50c2a1ca]
[pkrvmpptgkbjq6m:10734] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c50c2a28b]
[pkrvmpptgkbjq6m:10734] [11] plumed_master(+0x15365)[0x557142856365]
[pkrvmpptgkbjq6m:10734] *** End of error message ***
</pre>
{% endraw %}
