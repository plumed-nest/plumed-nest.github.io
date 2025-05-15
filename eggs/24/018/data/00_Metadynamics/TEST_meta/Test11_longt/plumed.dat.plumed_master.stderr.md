**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmberfyhpb9w:06056] *** Process received signal ***
[pkrvmberfyhpb9w:06056] Signal: Aborted (6)
[pkrvmberfyhpb9w:06056] Signal code:  (-6)
[pkrvmberfyhpb9w:06056] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a86245330]
[pkrvmberfyhpb9w:06056] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a8629eb2c]
[pkrvmberfyhpb9w:06056] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a8624527e]
[pkrvmberfyhpb9w:06056] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a862288ff]
[pkrvmberfyhpb9w:06056] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a866a5ff5]
[pkrvmberfyhpb9w:06056] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a866bb0da]
[pkrvmberfyhpb9w:06056] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a866a5a55]
[pkrvmberfyhpb9w:06056] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a866a5a6f]
[pkrvmberfyhpb9w:06056] [ 8] plumed_master(+0x146dd)[0x55bf1fe5e6dd]
[pkrvmberfyhpb9w:06056] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a8622a1ca]
[pkrvmberfyhpb9w:06056] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a8622a28b]
[pkrvmberfyhpb9w:06056] [11] plumed_master(+0x15365)[0x55bf1fe5f365]
[pkrvmberfyhpb9w:06056] *** End of error message ***
</pre>
{% endraw %}
