**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmberfyhpb9w:06109] *** Process received signal ***
[pkrvmberfyhpb9w:06109] Signal: Aborted (6)
[pkrvmberfyhpb9w:06109] Signal code:  (-6)
[pkrvmberfyhpb9w:06109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0973845330]
[pkrvmberfyhpb9w:06109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f097389eb2c]
[pkrvmberfyhpb9w:06109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f097384527e]
[pkrvmberfyhpb9w:06109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09738288ff]
[pkrvmberfyhpb9w:06109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0973ca5ff5]
[pkrvmberfyhpb9w:06109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0973cbb0da]
[pkrvmberfyhpb9w:06109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0973ca5a55]
[pkrvmberfyhpb9w:06109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0973ca5a6f]
[pkrvmberfyhpb9w:06109] [ 8] plumed_master(+0x146dd)[0x556e845ad6dd]
[pkrvmberfyhpb9w:06109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f097382a1ca]
[pkrvmberfyhpb9w:06109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f097382a28b]
[pkrvmberfyhpb9w:06109] [11] plumed_master(+0x15365)[0x556e845ae365]
[pkrvmberfyhpb9w:06109] *** End of error message ***
</pre>
{% endraw %}
