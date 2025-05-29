**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmf6wy0o8zjz:62591] *** Process received signal ***
[pkrvmf6wy0o8zjz:62591] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62591] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62591] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff443045330]
[pkrvmf6wy0o8zjz:62591] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff44309eb2c]
[pkrvmf6wy0o8zjz:62591] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff44304527e]
[pkrvmf6wy0o8zjz:62591] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff4430288ff]
[pkrvmf6wy0o8zjz:62591] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4434a5ff5]
[pkrvmf6wy0o8zjz:62591] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4434bb0da]
[pkrvmf6wy0o8zjz:62591] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4434a5a55]
[pkrvmf6wy0o8zjz:62591] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4434a5a6f]
[pkrvmf6wy0o8zjz:62591] [ 8] plumed(+0x146dd)[0x5646381266dd]
[pkrvmf6wy0o8zjz:62591] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff44302a1ca]
[pkrvmf6wy0o8zjz:62591] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff44302a28b]
[pkrvmf6wy0o8zjz:62591] [11] plumed(+0x15365)[0x564638127365]
[pkrvmf6wy0o8zjz:62591] *** End of error message ***
</pre>
{% endraw %}
