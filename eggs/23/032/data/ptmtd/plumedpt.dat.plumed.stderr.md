**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmpptgkbjq6m:07722] *** Process received signal ***
[pkrvmpptgkbjq6m:07722] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07722] Signal code:  (-6)
[pkrvmpptgkbjq6m:07722] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb30445330]
[pkrvmpptgkbjq6m:07722] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb3049eb2c]
[pkrvmpptgkbjq6m:07722] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb3044527e]
[pkrvmpptgkbjq6m:07722] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb304288ff]
[pkrvmpptgkbjq6m:07722] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb308a5ff5]
[pkrvmpptgkbjq6m:07722] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb308bb0da]
[pkrvmpptgkbjq6m:07722] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb308a5a55]
[pkrvmpptgkbjq6m:07722] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb308a5a6f]
[pkrvmpptgkbjq6m:07722] [ 8] plumed(+0x146dd)[0x56362e5946dd]
[pkrvmpptgkbjq6m:07722] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb3042a1ca]
[pkrvmpptgkbjq6m:07722] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb3042a28b]
[pkrvmpptgkbjq6m:07722] [11] plumed(+0x15365)[0x56362e595365]
[pkrvmpptgkbjq6m:07722] *** End of error message ***
</pre>
{% endraw %}
