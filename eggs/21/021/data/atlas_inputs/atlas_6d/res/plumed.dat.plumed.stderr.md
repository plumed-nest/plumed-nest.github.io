**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[pkrvmberfyhpb9w:10333] *** Process received signal ***
[pkrvmberfyhpb9w:10333] Signal: Aborted (6)
[pkrvmberfyhpb9w:10333] Signal code:  (-6)
[pkrvmberfyhpb9w:10333] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe940645330]
[pkrvmberfyhpb9w:10333] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe94069eb2c]
[pkrvmberfyhpb9w:10333] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe94064527e]
[pkrvmberfyhpb9w:10333] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9406288ff]
[pkrvmberfyhpb9w:10333] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe940aa5ff5]
[pkrvmberfyhpb9w:10333] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe940abb0da]
[pkrvmberfyhpb9w:10333] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe940aa5a55]
[pkrvmberfyhpb9w:10333] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe940aa5a6f]
[pkrvmberfyhpb9w:10333] [ 8] plumed(+0x146dd)[0x55c4283c76dd]
[pkrvmberfyhpb9w:10333] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe94062a1ca]
[pkrvmberfyhpb9w:10333] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe94062a28b]
[pkrvmberfyhpb9w:10333] [11] plumed(+0x15365)[0x55c4283c8365]
[pkrvmberfyhpb9w:10333] *** End of error message ***
</pre>
{% endraw %}
