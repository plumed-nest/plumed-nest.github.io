**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmf6wy0o8zjz:63415] *** Process received signal ***
[pkrvmf6wy0o8zjz:63415] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63415] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63415] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3ab8e45330]
[pkrvmf6wy0o8zjz:63415] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3ab8e9eb2c]
[pkrvmf6wy0o8zjz:63415] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3ab8e4527e]
[pkrvmf6wy0o8zjz:63415] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3ab8e288ff]
[pkrvmf6wy0o8zjz:63415] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3ab92a5ff5]
[pkrvmf6wy0o8zjz:63415] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3ab92bb0da]
[pkrvmf6wy0o8zjz:63415] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3ab92a5a55]
[pkrvmf6wy0o8zjz:63415] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3ab92a5a6f]
[pkrvmf6wy0o8zjz:63415] [ 8] plumed(+0x146dd)[0x55aa459426dd]
[pkrvmf6wy0o8zjz:63415] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3ab8e2a1ca]
[pkrvmf6wy0o8zjz:63415] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3ab8e2a28b]
[pkrvmf6wy0o8zjz:63415] [11] plumed(+0x15365)[0x55aa45943365]
[pkrvmf6wy0o8zjz:63415] *** End of error message ***
</pre>
{% endraw %}
