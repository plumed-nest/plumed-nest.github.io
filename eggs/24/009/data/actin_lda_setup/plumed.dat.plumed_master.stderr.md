**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[pkrvmpptgkbjq6m:07600] *** Process received signal ***
[pkrvmpptgkbjq6m:07600] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07600] Signal code:  (-6)
[pkrvmpptgkbjq6m:07600] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6950c45330]
[pkrvmpptgkbjq6m:07600] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6950c9eb2c]
[pkrvmpptgkbjq6m:07600] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6950c4527e]
[pkrvmpptgkbjq6m:07600] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6950c288ff]
[pkrvmpptgkbjq6m:07600] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69510a5ff5]
[pkrvmpptgkbjq6m:07600] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69510bb0da]
[pkrvmpptgkbjq6m:07600] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69510a5a55]
[pkrvmpptgkbjq6m:07600] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69510a5a6f]
[pkrvmpptgkbjq6m:07600] [ 8] plumed_master(+0x146dd)[0x555b1096a6dd]
[pkrvmpptgkbjq6m:07600] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6950c2a1ca]
[pkrvmpptgkbjq6m:07600] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6950c2a28b]
[pkrvmpptgkbjq6m:07600] [11] plumed_master(+0x15365)[0x555b1096b365]
[pkrvmpptgkbjq6m:07600] *** End of error message ***
</pre>
{% endraw %}
