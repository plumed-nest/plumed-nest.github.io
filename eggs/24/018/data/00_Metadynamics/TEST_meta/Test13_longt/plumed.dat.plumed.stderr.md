**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmxyh4eaekms:06528] *** Process received signal ***
[pkrvmxyh4eaekms:06528] Signal: Aborted (6)
[pkrvmxyh4eaekms:06528] Signal code:  (-6)
[pkrvmxyh4eaekms:06528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ea2645330]
[pkrvmxyh4eaekms:06528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ea269eb2c]
[pkrvmxyh4eaekms:06528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ea264527e]
[pkrvmxyh4eaekms:06528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ea26288ff]
[pkrvmxyh4eaekms:06528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ea2aa5ff5]
[pkrvmxyh4eaekms:06528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ea2abb0da]
[pkrvmxyh4eaekms:06528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ea2aa5a55]
[pkrvmxyh4eaekms:06528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ea2aa5a6f]
[pkrvmxyh4eaekms:06528] [ 8] plumed(+0x146dd)[0x5598094376dd]
[pkrvmxyh4eaekms:06528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ea262a1ca]
[pkrvmxyh4eaekms:06528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ea262a28b]
[pkrvmxyh4eaekms:06528] [11] plumed(+0x15365)[0x559809438365]
[pkrvmxyh4eaekms:06528] *** End of error message ***
</pre>
{% endraw %}
