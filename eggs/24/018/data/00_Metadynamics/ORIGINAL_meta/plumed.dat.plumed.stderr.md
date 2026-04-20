**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/ORIGINAL_meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06089] *** Process received signal ***
[runnervmeorf1:06089] Signal: Aborted (6)
[runnervmeorf1:06089] Signal code:  (-6)
[runnervmeorf1:06089] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4f49a45330]
[runnervmeorf1:06089] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4f49a9eb2c]
[runnervmeorf1:06089] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4f49a4527e]
[runnervmeorf1:06089] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4f49a288ff]
[runnervmeorf1:06089] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4f49ea5ff5]
[runnervmeorf1:06089] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4f49ebb0da]
[runnervmeorf1:06089] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4f49ea5a55]
[runnervmeorf1:06089] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4f49ea5a6f]
[runnervmeorf1:06089] [ 8] plumed(+0x146dd)[0x56441c9c66dd]
[runnervmeorf1:06089] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4f49a2a1ca]
[runnervmeorf1:06089] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4f49a2a28b]
[runnervmeorf1:06089] [11] plumed(+0x15365)[0x56441c9c7365]
[runnervmeorf1:06089] *** End of error message ***
</pre>
{% endraw %}
