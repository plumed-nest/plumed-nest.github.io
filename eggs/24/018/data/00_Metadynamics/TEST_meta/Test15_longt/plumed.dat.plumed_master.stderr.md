**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmberfyhpb9w:06262] *** Process received signal ***
[pkrvmberfyhpb9w:06262] Signal: Aborted (6)
[pkrvmberfyhpb9w:06262] Signal code:  (-6)
[pkrvmberfyhpb9w:06262] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19de245330]
[pkrvmberfyhpb9w:06262] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19de29eb2c]
[pkrvmberfyhpb9w:06262] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19de24527e]
[pkrvmberfyhpb9w:06262] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19de2288ff]
[pkrvmberfyhpb9w:06262] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19de6a5ff5]
[pkrvmberfyhpb9w:06262] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19de6bb0da]
[pkrvmberfyhpb9w:06262] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19de6a5a55]
[pkrvmberfyhpb9w:06262] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19de6a5a6f]
[pkrvmberfyhpb9w:06262] [ 8] plumed_master(+0x146dd)[0x55a82a0ce6dd]
[pkrvmberfyhpb9w:06262] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19de22a1ca]
[pkrvmberfyhpb9w:06262] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19de22a28b]
[pkrvmberfyhpb9w:06262] [11] plumed_master(+0x15365)[0x55a82a0cf365]
[pkrvmberfyhpb9w:06262] *** End of error message ***
</pre>
{% endraw %}
