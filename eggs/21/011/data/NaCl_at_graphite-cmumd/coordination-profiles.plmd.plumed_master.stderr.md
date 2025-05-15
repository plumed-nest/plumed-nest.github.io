**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvmberfyhpb9w:10544] *** Process received signal ***
[pkrvmberfyhpb9w:10544] Signal: Aborted (6)
[pkrvmberfyhpb9w:10544] Signal code:  (-6)
[pkrvmberfyhpb9w:10544] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe54445330]
[pkrvmberfyhpb9w:10544] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe5449eb2c]
[pkrvmberfyhpb9w:10544] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe5444527e]
[pkrvmberfyhpb9w:10544] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe544288ff]
[pkrvmberfyhpb9w:10544] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe548a5ff5]
[pkrvmberfyhpb9w:10544] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe548bb0da]
[pkrvmberfyhpb9w:10544] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe548a5a55]
[pkrvmberfyhpb9w:10544] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe548a5a6f]
[pkrvmberfyhpb9w:10544] [ 8] plumed_master(+0x146dd)[0x55a676f5f6dd]
[pkrvmberfyhpb9w:10544] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe5442a1ca]
[pkrvmberfyhpb9w:10544] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe5442a28b]
[pkrvmberfyhpb9w:10544] [11] plumed_master(+0x15365)[0x55a676f60365]
[pkrvmberfyhpb9w:10544] *** End of error message ***
</pre>
{% endraw %}
