**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmberfyhpb9w:06093] *** Process received signal ***
[pkrvmberfyhpb9w:06093] Signal: Aborted (6)
[pkrvmberfyhpb9w:06093] Signal code:  (-6)
[pkrvmberfyhpb9w:06093] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa71c45330]
[pkrvmberfyhpb9w:06093] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa71c9eb2c]
[pkrvmberfyhpb9w:06093] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa71c4527e]
[pkrvmberfyhpb9w:06093] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa71c288ff]
[pkrvmberfyhpb9w:06093] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa720a5ff5]
[pkrvmberfyhpb9w:06093] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa720bb0da]
[pkrvmberfyhpb9w:06093] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa720a5a55]
[pkrvmberfyhpb9w:06093] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa720a5a6f]
[pkrvmberfyhpb9w:06093] [ 8] plumed(+0x146dd)[0x55e1dc6b56dd]
[pkrvmberfyhpb9w:06093] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa71c2a1ca]
[pkrvmberfyhpb9w:06093] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa71c2a28b]
[pkrvmberfyhpb9w:06093] [11] plumed(+0x15365)[0x55e1dc6b6365]
[pkrvmberfyhpb9w:06093] *** End of error message ***
</pre>
{% endraw %}
