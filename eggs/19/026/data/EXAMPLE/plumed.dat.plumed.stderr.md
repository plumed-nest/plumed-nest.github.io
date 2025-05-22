**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmf6wy0o8zjz:42708] *** Process received signal ***
[pkrvmf6wy0o8zjz:42708] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:42708] Signal code:  (-6)
[pkrvmf6wy0o8zjz:42708] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f188e045330]
[pkrvmf6wy0o8zjz:42708] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f188e09eb2c]
[pkrvmf6wy0o8zjz:42708] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f188e04527e]
[pkrvmf6wy0o8zjz:42708] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f188e0288ff]
[pkrvmf6wy0o8zjz:42708] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f188e4a5ff5]
[pkrvmf6wy0o8zjz:42708] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f188e4bb0da]
[pkrvmf6wy0o8zjz:42708] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f188e4a5a55]
[pkrvmf6wy0o8zjz:42708] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f188e4a5a6f]
[pkrvmf6wy0o8zjz:42708] [ 8] plumed(+0x146dd)[0x55b9c58816dd]
[pkrvmf6wy0o8zjz:42708] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f188e02a1ca]
[pkrvmf6wy0o8zjz:42708] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f188e02a28b]
[pkrvmf6wy0o8zjz:42708] [11] plumed(+0x15365)[0x55b9c5882365]
[pkrvmf6wy0o8zjz:42708] *** End of error message ***
</pre>
{% endraw %}
