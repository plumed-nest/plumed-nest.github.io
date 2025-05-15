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
[pkrvmberfyhpb9w:06144] *** Process received signal ***
[pkrvmberfyhpb9w:06144] Signal: Aborted (6)
[pkrvmberfyhpb9w:06144] Signal code:  (-6)
[pkrvmberfyhpb9w:06144] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f322aa45330]
[pkrvmberfyhpb9w:06144] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f322aa9eb2c]
[pkrvmberfyhpb9w:06144] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f322aa4527e]
[pkrvmberfyhpb9w:06144] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f322aa288ff]
[pkrvmberfyhpb9w:06144] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f322aea5ff5]
[pkrvmberfyhpb9w:06144] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f322aebb0da]
[pkrvmberfyhpb9w:06144] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f322aea5a55]
[pkrvmberfyhpb9w:06144] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f322aea5a6f]
[pkrvmberfyhpb9w:06144] [ 8] plumed(+0x146dd)[0x55df765da6dd]
[pkrvmberfyhpb9w:06144] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f322aa2a1ca]
[pkrvmberfyhpb9w:06144] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f322aa2a28b]
[pkrvmberfyhpb9w:06144] [11] plumed(+0x15365)[0x55df765db365]
[pkrvmberfyhpb9w:06144] *** End of error message ***
</pre>
{% endraw %}
