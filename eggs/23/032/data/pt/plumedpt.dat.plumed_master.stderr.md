**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmpptgkbjq6m:07684] *** Process received signal ***
[pkrvmpptgkbjq6m:07684] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07684] Signal code:  (-6)
[pkrvmpptgkbjq6m:07684] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe536045330]
[pkrvmpptgkbjq6m:07684] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe53609eb2c]
[pkrvmpptgkbjq6m:07684] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe53604527e]
[pkrvmpptgkbjq6m:07684] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5360288ff]
[pkrvmpptgkbjq6m:07684] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5364a5ff5]
[pkrvmpptgkbjq6m:07684] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5364bb0da]
[pkrvmpptgkbjq6m:07684] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5364a5a55]
[pkrvmpptgkbjq6m:07684] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5364a5a6f]
[pkrvmpptgkbjq6m:07684] [ 8] plumed_master(+0x146dd)[0x55b7eeb446dd]
[pkrvmpptgkbjq6m:07684] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe53602a1ca]
[pkrvmpptgkbjq6m:07684] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe53602a28b]
[pkrvmpptgkbjq6m:07684] [11] plumed_master(+0x15365)[0x55b7eeb45365]
[pkrvmpptgkbjq6m:07684] *** End of error message ***
</pre>
{% endraw %}
