**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmpptgkbjq6m:07738] *** Process received signal ***
[pkrvmpptgkbjq6m:07738] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07738] Signal code:  (-6)
[pkrvmpptgkbjq6m:07738] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f796a645330]
[pkrvmpptgkbjq6m:07738] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f796a69eb2c]
[pkrvmpptgkbjq6m:07738] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f796a64527e]
[pkrvmpptgkbjq6m:07738] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f796a6288ff]
[pkrvmpptgkbjq6m:07738] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f796aaa5ff5]
[pkrvmpptgkbjq6m:07738] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f796aabb0da]
[pkrvmpptgkbjq6m:07738] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f796aaa5a55]
[pkrvmpptgkbjq6m:07738] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f796aaa5a6f]
[pkrvmpptgkbjq6m:07738] [ 8] plumed_master(+0x146dd)[0x559a904746dd]
[pkrvmpptgkbjq6m:07738] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f796a62a1ca]
[pkrvmpptgkbjq6m:07738] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f796a62a28b]
[pkrvmpptgkbjq6m:07738] [11] plumed_master(+0x15365)[0x559a90475365]
[pkrvmpptgkbjq6m:07738] *** End of error message ***
</pre>
{% endraw %}
