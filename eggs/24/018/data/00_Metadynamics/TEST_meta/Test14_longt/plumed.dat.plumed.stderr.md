**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmxyh4eaekms:06579] *** Process received signal ***
[pkrvmxyh4eaekms:06579] Signal: Aborted (6)
[pkrvmxyh4eaekms:06579] Signal code:  (-6)
[pkrvmxyh4eaekms:06579] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b4ae45330]
[pkrvmxyh4eaekms:06579] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b4ae9eb2c]
[pkrvmxyh4eaekms:06579] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b4ae4527e]
[pkrvmxyh4eaekms:06579] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b4ae288ff]
[pkrvmxyh4eaekms:06579] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b4b2a5ff5]
[pkrvmxyh4eaekms:06579] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b4b2bb0da]
[pkrvmxyh4eaekms:06579] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b4b2a5a55]
[pkrvmxyh4eaekms:06579] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b4b2a5a6f]
[pkrvmxyh4eaekms:06579] [ 8] plumed(+0x146dd)[0x55e3cf87f6dd]
[pkrvmxyh4eaekms:06579] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b4ae2a1ca]
[pkrvmxyh4eaekms:06579] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b4ae2a28b]
[pkrvmxyh4eaekms:06579] [11] plumed(+0x15365)[0x55e3cf880365]
[pkrvmxyh4eaekms:06579] *** End of error message ***
</pre>
{% endraw %}
