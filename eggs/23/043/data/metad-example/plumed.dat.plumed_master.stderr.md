**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmf6wy0o8zjz:62606] *** Process received signal ***
[pkrvmf6wy0o8zjz:62606] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62606] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62606] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f433b845330]
[pkrvmf6wy0o8zjz:62606] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f433b89eb2c]
[pkrvmf6wy0o8zjz:62606] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f433b84527e]
[pkrvmf6wy0o8zjz:62606] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f433b8288ff]
[pkrvmf6wy0o8zjz:62606] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f433bca5ff5]
[pkrvmf6wy0o8zjz:62606] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f433bcbb0da]
[pkrvmf6wy0o8zjz:62606] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f433bca5a55]
[pkrvmf6wy0o8zjz:62606] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f433bca5a6f]
[pkrvmf6wy0o8zjz:62606] [ 8] plumed_master(+0x146dd)[0x562e4496b6dd]
[pkrvmf6wy0o8zjz:62606] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f433b82a1ca]
[pkrvmf6wy0o8zjz:62606] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f433b82a28b]
[pkrvmf6wy0o8zjz:62606] [11] plumed_master(+0x15365)[0x562e4496c365]
[pkrvmf6wy0o8zjz:62606] *** End of error message ***
</pre>
{% endraw %}
