**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmberfyhpb9w:14180] *** Process received signal ***
[pkrvmberfyhpb9w:14180] Signal: Aborted (6)
[pkrvmberfyhpb9w:14180] Signal code:  (-6)
[pkrvmberfyhpb9w:14180] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbaca445330]
[pkrvmberfyhpb9w:14180] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbaca49eb2c]
[pkrvmberfyhpb9w:14180] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbaca44527e]
[pkrvmberfyhpb9w:14180] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbaca4288ff]
[pkrvmberfyhpb9w:14180] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbaca8a5ff5]
[pkrvmberfyhpb9w:14180] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbaca8bb0da]
[pkrvmberfyhpb9w:14180] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbaca8a5a55]
[pkrvmberfyhpb9w:14180] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbaca8a5a6f]
[pkrvmberfyhpb9w:14180] [ 8] plumed_master(+0x146dd)[0x560e2a7e66dd]
[pkrvmberfyhpb9w:14180] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbaca42a1ca]
[pkrvmberfyhpb9w:14180] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbaca42a28b]
[pkrvmberfyhpb9w:14180] [11] plumed_master(+0x15365)[0x560e2a7e7365]
[pkrvmberfyhpb9w:14180] *** End of error message ***
</pre>
{% endraw %}
