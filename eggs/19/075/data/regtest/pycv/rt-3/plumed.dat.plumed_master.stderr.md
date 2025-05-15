**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmberfyhpb9w:12646] *** Process received signal ***
[pkrvmberfyhpb9w:12646] Signal: Aborted (6)
[pkrvmberfyhpb9w:12646] Signal code:  (-6)
[pkrvmberfyhpb9w:12646] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb352245330]
[pkrvmberfyhpb9w:12646] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb35229eb2c]
[pkrvmberfyhpb9w:12646] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb35224527e]
[pkrvmberfyhpb9w:12646] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb3522288ff]
[pkrvmberfyhpb9w:12646] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb3526a5ff5]
[pkrvmberfyhpb9w:12646] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb3526bb0da]
[pkrvmberfyhpb9w:12646] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb3526a5a55]
[pkrvmberfyhpb9w:12646] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb3526a5a6f]
[pkrvmberfyhpb9w:12646] [ 8] plumed_master(+0x146dd)[0x55c375a6e6dd]
[pkrvmberfyhpb9w:12646] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb35222a1ca]
[pkrvmberfyhpb9w:12646] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb35222a28b]
[pkrvmberfyhpb9w:12646] [11] plumed_master(+0x15365)[0x55c375a6f365]
[pkrvmberfyhpb9w:12646] *** End of error message ***
</pre>
{% endraw %}
