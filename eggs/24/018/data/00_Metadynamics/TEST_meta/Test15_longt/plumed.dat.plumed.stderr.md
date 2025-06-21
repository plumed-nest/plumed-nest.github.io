**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmxyh4eaekms:06631] *** Process received signal ***
[pkrvmxyh4eaekms:06631] Signal: Aborted (6)
[pkrvmxyh4eaekms:06631] Signal code:  (-6)
[pkrvmxyh4eaekms:06631] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efd6e045330]
[pkrvmxyh4eaekms:06631] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efd6e09eb2c]
[pkrvmxyh4eaekms:06631] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efd6e04527e]
[pkrvmxyh4eaekms:06631] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efd6e0288ff]
[pkrvmxyh4eaekms:06631] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efd6e4a5ff5]
[pkrvmxyh4eaekms:06631] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efd6e4bb0da]
[pkrvmxyh4eaekms:06631] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efd6e4a5a55]
[pkrvmxyh4eaekms:06631] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efd6e4a5a6f]
[pkrvmxyh4eaekms:06631] [ 8] plumed(+0x146dd)[0x563c48ba06dd]
[pkrvmxyh4eaekms:06631] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efd6e02a1ca]
[pkrvmxyh4eaekms:06631] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efd6e02a28b]
[pkrvmxyh4eaekms:06631] [11] plumed(+0x15365)[0x563c48ba1365]
[pkrvmxyh4eaekms:06631] *** End of error message ***
</pre>
{% endraw %}
