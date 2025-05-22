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
[pkrvmf6wy0o8zjz:33855] *** Process received signal ***
[pkrvmf6wy0o8zjz:33855] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:33855] Signal code:  (-6)
[pkrvmf6wy0o8zjz:33855] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd106c45330]
[pkrvmf6wy0o8zjz:33855] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd106c9eb2c]
[pkrvmf6wy0o8zjz:33855] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd106c4527e]
[pkrvmf6wy0o8zjz:33855] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd106c288ff]
[pkrvmf6wy0o8zjz:33855] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1070a5ff5]
[pkrvmf6wy0o8zjz:33855] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1070bb0da]
[pkrvmf6wy0o8zjz:33855] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1070a5a55]
[pkrvmf6wy0o8zjz:33855] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1070a5a6f]
[pkrvmf6wy0o8zjz:33855] [ 8] plumed(+0x146dd)[0x558cc11ac6dd]
[pkrvmf6wy0o8zjz:33855] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd106c2a1ca]
[pkrvmf6wy0o8zjz:33855] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd106c2a28b]
[pkrvmf6wy0o8zjz:33855] [11] plumed(+0x15365)[0x558cc11ad365]
[pkrvmf6wy0o8zjz:33855] *** End of error message ***
</pre>
{% endraw %}
