**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmberfyhpb9w:14164] *** Process received signal ***
[pkrvmberfyhpb9w:14164] Signal: Aborted (6)
[pkrvmberfyhpb9w:14164] Signal code:  (-6)
[pkrvmberfyhpb9w:14164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1268c45330]
[pkrvmberfyhpb9w:14164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1268c9eb2c]
[pkrvmberfyhpb9w:14164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1268c4527e]
[pkrvmberfyhpb9w:14164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1268c288ff]
[pkrvmberfyhpb9w:14164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12690a5ff5]
[pkrvmberfyhpb9w:14164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12690bb0da]
[pkrvmberfyhpb9w:14164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12690a5a55]
[pkrvmberfyhpb9w:14164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12690a5a6f]
[pkrvmberfyhpb9w:14164] [ 8] plumed(+0x146dd)[0x5576749556dd]
[pkrvmberfyhpb9w:14164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1268c2a1ca]
[pkrvmberfyhpb9w:14164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1268c2a28b]
[pkrvmberfyhpb9w:14164] [11] plumed(+0x15365)[0x557674956365]
[pkrvmberfyhpb9w:14164] *** End of error message ***
</pre>
{% endraw %}
