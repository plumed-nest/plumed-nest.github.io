**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[pkrvmberfyhpb9w:12750] *** Process received signal ***
[pkrvmberfyhpb9w:12750] Signal: Aborted (6)
[pkrvmberfyhpb9w:12750] Signal code:  (-6)
[pkrvmberfyhpb9w:12750] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e20c45330]
[pkrvmberfyhpb9w:12750] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e20c9eb2c]
[pkrvmberfyhpb9w:12750] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e20c4527e]
[pkrvmberfyhpb9w:12750] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e20c288ff]
[pkrvmberfyhpb9w:12750] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e210a5ff5]
[pkrvmberfyhpb9w:12750] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e210bb0da]
[pkrvmberfyhpb9w:12750] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e210a5a55]
[pkrvmberfyhpb9w:12750] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e210a5a6f]
[pkrvmberfyhpb9w:12750] [ 8] plumed_master(+0x146dd)[0x5649443b66dd]
[pkrvmberfyhpb9w:12750] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e20c2a1ca]
[pkrvmberfyhpb9w:12750] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e20c2a28b]
[pkrvmberfyhpb9w:12750] [11] plumed_master(+0x15365)[0x5649443b7365]
[pkrvmberfyhpb9w:12750] *** End of error message ***
</pre>
{% endraw %}
