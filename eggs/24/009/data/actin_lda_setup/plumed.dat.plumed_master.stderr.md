**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[pkrvmberfyhpb9w:06730] *** Process received signal ***
[pkrvmberfyhpb9w:06730] Signal: Aborted (6)
[pkrvmberfyhpb9w:06730] Signal code:  (-6)
[pkrvmberfyhpb9w:06730] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e45c45330]
[pkrvmberfyhpb9w:06730] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e45c9eb2c]
[pkrvmberfyhpb9w:06730] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e45c4527e]
[pkrvmberfyhpb9w:06730] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e45c288ff]
[pkrvmberfyhpb9w:06730] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e460a5ff5]
[pkrvmberfyhpb9w:06730] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e460bb0da]
[pkrvmberfyhpb9w:06730] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e460a5a55]
[pkrvmberfyhpb9w:06730] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e460a5a6f]
[pkrvmberfyhpb9w:06730] [ 8] plumed_master(+0x146dd)[0x55c86a0706dd]
[pkrvmberfyhpb9w:06730] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e45c2a1ca]
[pkrvmberfyhpb9w:06730] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e45c2a28b]
[pkrvmberfyhpb9w:06730] [11] plumed_master(+0x15365)[0x55c86a071365]
[pkrvmberfyhpb9w:06730] *** End of error message ***
</pre>
{% endraw %}
