**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmf6wy0o8zjz:37110] *** Process received signal ***
[pkrvmf6wy0o8zjz:37110] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37110] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37110] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9790c45330]
[pkrvmf6wy0o8zjz:37110] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9790c9eb2c]
[pkrvmf6wy0o8zjz:37110] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9790c4527e]
[pkrvmf6wy0o8zjz:37110] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9790c288ff]
[pkrvmf6wy0o8zjz:37110] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97910a5ff5]
[pkrvmf6wy0o8zjz:37110] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97910bb0da]
[pkrvmf6wy0o8zjz:37110] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97910a5a55]
[pkrvmf6wy0o8zjz:37110] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97910a5a6f]
[pkrvmf6wy0o8zjz:37110] [ 8] plumed_master(+0x146dd)[0x55f66c61c6dd]
[pkrvmf6wy0o8zjz:37110] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9790c2a1ca]
[pkrvmf6wy0o8zjz:37110] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9790c2a28b]
[pkrvmf6wy0o8zjz:37110] [11] plumed_master(+0x15365)[0x55f66c61d365]
[pkrvmf6wy0o8zjz:37110] *** End of error message ***
</pre>
{% endraw %}
