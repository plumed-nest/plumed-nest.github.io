**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmf6wy0o8zjz:62711] *** Process received signal ***
[pkrvmf6wy0o8zjz:62711] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62711] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62711] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efdf0445330]
[pkrvmf6wy0o8zjz:62711] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efdf049eb2c]
[pkrvmf6wy0o8zjz:62711] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efdf044527e]
[pkrvmf6wy0o8zjz:62711] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efdf04288ff]
[pkrvmf6wy0o8zjz:62711] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efdf08a5ff5]
[pkrvmf6wy0o8zjz:62711] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efdf08bb0da]
[pkrvmf6wy0o8zjz:62711] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efdf08a5a55]
[pkrvmf6wy0o8zjz:62711] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efdf08a5a6f]
[pkrvmf6wy0o8zjz:62711] [ 8] plumed_master(+0x146dd)[0x55fd4bf066dd]
[pkrvmf6wy0o8zjz:62711] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efdf042a1ca]
[pkrvmf6wy0o8zjz:62711] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efdf042a28b]
[pkrvmf6wy0o8zjz:62711] [11] plumed_master(+0x15365)[0x55fd4bf07365]
[pkrvmf6wy0o8zjz:62711] *** End of error message ***
</pre>
{% endraw %}
