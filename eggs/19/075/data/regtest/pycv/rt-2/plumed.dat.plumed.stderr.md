**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmberfyhpb9w:12578] *** Process received signal ***
[pkrvmberfyhpb9w:12578] Signal: Aborted (6)
[pkrvmberfyhpb9w:12578] Signal code:  (-6)
[pkrvmberfyhpb9w:12578] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3dfe845330]
[pkrvmberfyhpb9w:12578] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3dfe89eb2c]
[pkrvmberfyhpb9w:12578] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3dfe84527e]
[pkrvmberfyhpb9w:12578] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3dfe8288ff]
[pkrvmberfyhpb9w:12578] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3dfeca5ff5]
[pkrvmberfyhpb9w:12578] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3dfecbb0da]
[pkrvmberfyhpb9w:12578] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3dfeca5a55]
[pkrvmberfyhpb9w:12578] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3dfeca5a6f]
[pkrvmberfyhpb9w:12578] [ 8] plumed(+0x146dd)[0x55f106b636dd]
[pkrvmberfyhpb9w:12578] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3dfe82a1ca]
[pkrvmberfyhpb9w:12578] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3dfe82a28b]
[pkrvmberfyhpb9w:12578] [11] plumed(+0x15365)[0x55f106b64365]
[pkrvmberfyhpb9w:12578] *** End of error message ***
</pre>
{% endraw %}
