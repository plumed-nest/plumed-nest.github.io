**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[pkrvmberfyhpb9w:10021] *** Process received signal ***
[pkrvmberfyhpb9w:10021] Signal: Aborted (6)
[pkrvmberfyhpb9w:10021] Signal code:  (-6)
[pkrvmberfyhpb9w:10021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbff9e45330]
[pkrvmberfyhpb9w:10021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbff9e9eb2c]
[pkrvmberfyhpb9w:10021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbff9e4527e]
[pkrvmberfyhpb9w:10021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbff9e288ff]
[pkrvmberfyhpb9w:10021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbffa2a5ff5]
[pkrvmberfyhpb9w:10021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbffa2bb0da]
[pkrvmberfyhpb9w:10021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbffa2a5a55]
[pkrvmberfyhpb9w:10021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbffa2a5a6f]
[pkrvmberfyhpb9w:10021] [ 8] plumed(+0x146dd)[0x555705adc6dd]
[pkrvmberfyhpb9w:10021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbff9e2a1ca]
[pkrvmberfyhpb9w:10021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbff9e2a28b]
[pkrvmberfyhpb9w:10021] [11] plumed(+0x15365)[0x555705add365]
[pkrvmberfyhpb9w:10021] *** End of error message ***
</pre>
{% endraw %}
