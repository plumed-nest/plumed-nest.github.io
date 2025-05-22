**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmf6wy0o8zjz:33905] *** Process received signal ***
[pkrvmf6wy0o8zjz:33905] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:33905] Signal code:  (-6)
[pkrvmf6wy0o8zjz:33905] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b14e45330]
[pkrvmf6wy0o8zjz:33905] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b14e9eb2c]
[pkrvmf6wy0o8zjz:33905] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b14e4527e]
[pkrvmf6wy0o8zjz:33905] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b14e288ff]
[pkrvmf6wy0o8zjz:33905] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b152a5ff5]
[pkrvmf6wy0o8zjz:33905] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b152bb0da]
[pkrvmf6wy0o8zjz:33905] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b152a5a55]
[pkrvmf6wy0o8zjz:33905] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b152a5a6f]
[pkrvmf6wy0o8zjz:33905] [ 8] plumed_master(+0x146dd)[0x55beb7afe6dd]
[pkrvmf6wy0o8zjz:33905] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b14e2a1ca]
[pkrvmf6wy0o8zjz:33905] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b14e2a28b]
[pkrvmf6wy0o8zjz:33905] [11] plumed_master(+0x15365)[0x55beb7aff365]
[pkrvmf6wy0o8zjz:33905] *** End of error message ***
</pre>
{% endraw %}
