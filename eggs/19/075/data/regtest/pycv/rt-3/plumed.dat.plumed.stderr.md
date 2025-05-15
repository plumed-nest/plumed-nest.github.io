**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmberfyhpb9w:12630] *** Process received signal ***
[pkrvmberfyhpb9w:12630] Signal: Aborted (6)
[pkrvmberfyhpb9w:12630] Signal code:  (-6)
[pkrvmberfyhpb9w:12630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f82ce445330]
[pkrvmberfyhpb9w:12630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f82ce49eb2c]
[pkrvmberfyhpb9w:12630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f82ce44527e]
[pkrvmberfyhpb9w:12630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82ce4288ff]
[pkrvmberfyhpb9w:12630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82ce8a5ff5]
[pkrvmberfyhpb9w:12630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82ce8bb0da]
[pkrvmberfyhpb9w:12630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82ce8a5a55]
[pkrvmberfyhpb9w:12630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82ce8a5a6f]
[pkrvmberfyhpb9w:12630] [ 8] plumed(+0x146dd)[0x561ed378d6dd]
[pkrvmberfyhpb9w:12630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f82ce42a1ca]
[pkrvmberfyhpb9w:12630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f82ce42a28b]
[pkrvmberfyhpb9w:12630] [11] plumed(+0x15365)[0x561ed378e365]
[pkrvmberfyhpb9w:12630] *** End of error message ***
</pre>
{% endraw %}
