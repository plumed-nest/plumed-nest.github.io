**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[pkrvmberfyhpb9w:09969] *** Process received signal ***
[pkrvmberfyhpb9w:09969] Signal: Aborted (6)
[pkrvmberfyhpb9w:09969] Signal code:  (-6)
[pkrvmberfyhpb9w:09969] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff13fa45330]
[pkrvmberfyhpb9w:09969] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff13fa9eb2c]
[pkrvmberfyhpb9w:09969] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff13fa4527e]
[pkrvmberfyhpb9w:09969] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff13fa288ff]
[pkrvmberfyhpb9w:09969] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff13fea5ff5]
[pkrvmberfyhpb9w:09969] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff13febb0da]
[pkrvmberfyhpb9w:09969] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff13fea5a55]
[pkrvmberfyhpb9w:09969] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff13fea5a6f]
[pkrvmberfyhpb9w:09969] [ 8] plumed(+0x146dd)[0x561da3f516dd]
[pkrvmberfyhpb9w:09969] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff13fa2a1ca]
[pkrvmberfyhpb9w:09969] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff13fa2a28b]
[pkrvmberfyhpb9w:09969] [11] plumed(+0x15365)[0x561da3f52365]
[pkrvmberfyhpb9w:09969] *** End of error message ***
</pre>
{% endraw %}
