**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmf6wy0o8zjz:34008] *** Process received signal ***
[pkrvmf6wy0o8zjz:34008] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34008] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f64df045330]
[pkrvmf6wy0o8zjz:34008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f64df09eb2c]
[pkrvmf6wy0o8zjz:34008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f64df04527e]
[pkrvmf6wy0o8zjz:34008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64df0288ff]
[pkrvmf6wy0o8zjz:34008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64df4a5ff5]
[pkrvmf6wy0o8zjz:34008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64df4bb0da]
[pkrvmf6wy0o8zjz:34008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64df4a5a55]
[pkrvmf6wy0o8zjz:34008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64df4a5a6f]
[pkrvmf6wy0o8zjz:34008] [ 8] plumed_master(+0x146dd)[0x55c1d8e916dd]
[pkrvmf6wy0o8zjz:34008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f64df02a1ca]
[pkrvmf6wy0o8zjz:34008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f64df02a28b]
[pkrvmf6wy0o8zjz:34008] [11] plumed_master(+0x15365)[0x55c1d8e92365]
[pkrvmf6wy0o8zjz:34008] *** End of error message ***
</pre>
{% endraw %}
