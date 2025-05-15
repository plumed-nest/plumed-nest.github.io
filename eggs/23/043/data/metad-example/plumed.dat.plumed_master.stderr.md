**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmberfyhpb9w:06597] *** Process received signal ***
[pkrvmberfyhpb9w:06597] Signal: Aborted (6)
[pkrvmberfyhpb9w:06597] Signal code:  (-6)
[pkrvmberfyhpb9w:06597] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e5e445330]
[pkrvmberfyhpb9w:06597] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e5e49eb2c]
[pkrvmberfyhpb9w:06597] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e5e44527e]
[pkrvmberfyhpb9w:06597] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e5e4288ff]
[pkrvmberfyhpb9w:06597] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e5e8a5ff5]
[pkrvmberfyhpb9w:06597] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e5e8bb0da]
[pkrvmberfyhpb9w:06597] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e5e8a5a55]
[pkrvmberfyhpb9w:06597] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e5e8a5a6f]
[pkrvmberfyhpb9w:06597] [ 8] plumed_master(+0x146dd)[0x556402a746dd]
[pkrvmberfyhpb9w:06597] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e5e42a1ca]
[pkrvmberfyhpb9w:06597] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e5e42a28b]
[pkrvmberfyhpb9w:06597] [11] plumed_master(+0x15365)[0x556402a75365]
[pkrvmberfyhpb9w:06597] *** End of error message ***
</pre>
{% endraw %}
