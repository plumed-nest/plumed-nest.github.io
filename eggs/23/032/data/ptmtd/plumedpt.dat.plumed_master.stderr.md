**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmberfyhpb9w:06543] *** Process received signal ***
[pkrvmberfyhpb9w:06543] Signal: Aborted (6)
[pkrvmberfyhpb9w:06543] Signal code:  (-6)
[pkrvmberfyhpb9w:06543] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a83e45330]
[pkrvmberfyhpb9w:06543] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a83e9eb2c]
[pkrvmberfyhpb9w:06543] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a83e4527e]
[pkrvmberfyhpb9w:06543] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a83e288ff]
[pkrvmberfyhpb9w:06543] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a842a5ff5]
[pkrvmberfyhpb9w:06543] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a842bb0da]
[pkrvmberfyhpb9w:06543] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a842a5a55]
[pkrvmberfyhpb9w:06543] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a842a5a6f]
[pkrvmberfyhpb9w:06543] [ 8] plumed_master(+0x146dd)[0x557e9bb066dd]
[pkrvmberfyhpb9w:06543] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a83e2a1ca]
[pkrvmberfyhpb9w:06543] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a83e2a28b]
[pkrvmberfyhpb9w:06543] [11] plumed_master(+0x15365)[0x557e9bb07365]
[pkrvmberfyhpb9w:06543] *** End of error message ***
</pre>
{% endraw %}
