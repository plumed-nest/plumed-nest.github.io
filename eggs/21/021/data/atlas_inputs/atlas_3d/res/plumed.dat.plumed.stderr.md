**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[pkrvmberfyhpb9w:10179] *** Process received signal ***
[pkrvmberfyhpb9w:10179] Signal: Aborted (6)
[pkrvmberfyhpb9w:10179] Signal code:  (-6)
[pkrvmberfyhpb9w:10179] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f821de45330]
[pkrvmberfyhpb9w:10179] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f821de9eb2c]
[pkrvmberfyhpb9w:10179] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f821de4527e]
[pkrvmberfyhpb9w:10179] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f821de288ff]
[pkrvmberfyhpb9w:10179] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f821e2a5ff5]
[pkrvmberfyhpb9w:10179] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f821e2bb0da]
[pkrvmberfyhpb9w:10179] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f821e2a5a55]
[pkrvmberfyhpb9w:10179] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f821e2a5a6f]
[pkrvmberfyhpb9w:10179] [ 8] plumed(+0x146dd)[0x560e0b7bd6dd]
[pkrvmberfyhpb9w:10179] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f821de2a1ca]
[pkrvmberfyhpb9w:10179] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f821de2a28b]
[pkrvmberfyhpb9w:10179] [11] plumed(+0x15365)[0x560e0b7be365]
[pkrvmberfyhpb9w:10179] *** End of error message ***
</pre>
{% endraw %}
