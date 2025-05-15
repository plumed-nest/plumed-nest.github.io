**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[pkrvmberfyhpb9w:11462] *** Process received signal ***
[pkrvmberfyhpb9w:11462] Signal: Aborted (6)
[pkrvmberfyhpb9w:11462] Signal code:  (-6)
[pkrvmberfyhpb9w:11462] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb261245330]
[pkrvmberfyhpb9w:11462] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb26129eb2c]
[pkrvmberfyhpb9w:11462] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb26124527e]
[pkrvmberfyhpb9w:11462] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2612288ff]
[pkrvmberfyhpb9w:11462] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb2616a5ff5]
[pkrvmberfyhpb9w:11462] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb2616bb0da]
[pkrvmberfyhpb9w:11462] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb2616a5a55]
[pkrvmberfyhpb9w:11462] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb2616a5a6f]
[pkrvmberfyhpb9w:11462] [ 8] plumed_master(+0x146dd)[0x5652392866dd]
[pkrvmberfyhpb9w:11462] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb26122a1ca]
[pkrvmberfyhpb9w:11462] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb26122a28b]
[pkrvmberfyhpb9w:11462] [11] plumed_master(+0x15365)[0x565239287365]
[pkrvmberfyhpb9w:11462] *** End of error message ***
</pre>
{% endraw %}
