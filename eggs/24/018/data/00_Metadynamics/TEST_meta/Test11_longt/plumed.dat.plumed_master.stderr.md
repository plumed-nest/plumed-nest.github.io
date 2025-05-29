**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmf6wy0o8zjz:62762] *** Process received signal ***
[pkrvmf6wy0o8zjz:62762] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62762] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62762] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d78245330]
[pkrvmf6wy0o8zjz:62762] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d7829eb2c]
[pkrvmf6wy0o8zjz:62762] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d7824527e]
[pkrvmf6wy0o8zjz:62762] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d782288ff]
[pkrvmf6wy0o8zjz:62762] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d786a5ff5]
[pkrvmf6wy0o8zjz:62762] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d786bb0da]
[pkrvmf6wy0o8zjz:62762] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d786a5a55]
[pkrvmf6wy0o8zjz:62762] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d786a5a6f]
[pkrvmf6wy0o8zjz:62762] [ 8] plumed_master(+0x146dd)[0x56451d3326dd]
[pkrvmf6wy0o8zjz:62762] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d7822a1ca]
[pkrvmf6wy0o8zjz:62762] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d7822a28b]
[pkrvmf6wy0o8zjz:62762] [11] plumed_master(+0x15365)[0x56451d333365]
[pkrvmf6wy0o8zjz:62762] *** End of error message ***
</pre>
{% endraw %}
