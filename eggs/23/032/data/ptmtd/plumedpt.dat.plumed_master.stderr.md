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
[pkrvmf6wy0o8zjz:63146] *** Process received signal ***
[pkrvmf6wy0o8zjz:63146] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63146] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe327045330]
[pkrvmf6wy0o8zjz:63146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe32709eb2c]
[pkrvmf6wy0o8zjz:63146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe32704527e]
[pkrvmf6wy0o8zjz:63146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3270288ff]
[pkrvmf6wy0o8zjz:63146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3274a5ff5]
[pkrvmf6wy0o8zjz:63146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3274bb0da]
[pkrvmf6wy0o8zjz:63146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3274a5a55]
[pkrvmf6wy0o8zjz:63146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3274a5a6f]
[pkrvmf6wy0o8zjz:63146] [ 8] plumed_master(+0x146dd)[0x55c7aef6b6dd]
[pkrvmf6wy0o8zjz:63146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe32702a1ca]
[pkrvmf6wy0o8zjz:63146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe32702a28b]
[pkrvmf6wy0o8zjz:63146] [11] plumed_master(+0x15365)[0x55c7aef6c365]
[pkrvmf6wy0o8zjz:63146] *** End of error message ***
</pre>
{% endraw %}
