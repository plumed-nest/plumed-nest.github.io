**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmberfyhpb9w:06160] *** Process received signal ***
[pkrvmberfyhpb9w:06160] Signal: Aborted (6)
[pkrvmberfyhpb9w:06160] Signal code:  (-6)
[pkrvmberfyhpb9w:06160] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2ab4045330]
[pkrvmberfyhpb9w:06160] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2ab409eb2c]
[pkrvmberfyhpb9w:06160] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2ab404527e]
[pkrvmberfyhpb9w:06160] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2ab40288ff]
[pkrvmberfyhpb9w:06160] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2ab44a5ff5]
[pkrvmberfyhpb9w:06160] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2ab44bb0da]
[pkrvmberfyhpb9w:06160] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2ab44a5a55]
[pkrvmberfyhpb9w:06160] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2ab44a5a6f]
[pkrvmberfyhpb9w:06160] [ 8] plumed_master(+0x146dd)[0x55ed43b666dd]
[pkrvmberfyhpb9w:06160] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2ab402a1ca]
[pkrvmberfyhpb9w:06160] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2ab402a28b]
[pkrvmberfyhpb9w:06160] [11] plumed_master(+0x15365)[0x55ed43b67365]
[pkrvmberfyhpb9w:06160] *** End of error message ***
</pre>
{% endraw %}
