**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmberfyhpb9w:06941] *** Process received signal ***
[pkrvmberfyhpb9w:06941] Signal: Aborted (6)
[pkrvmberfyhpb9w:06941] Signal code:  (-6)
[pkrvmberfyhpb9w:06941] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc4ffa45330]
[pkrvmberfyhpb9w:06941] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc4ffa9eb2c]
[pkrvmberfyhpb9w:06941] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc4ffa4527e]
[pkrvmberfyhpb9w:06941] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4ffa288ff]
[pkrvmberfyhpb9w:06941] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4ffea5ff5]
[pkrvmberfyhpb9w:06941] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4ffebb0da]
[pkrvmberfyhpb9w:06941] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4ffea5a55]
[pkrvmberfyhpb9w:06941] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4ffea5a6f]
[pkrvmberfyhpb9w:06941] [ 8] plumed_master(+0x146dd)[0x559804a6b6dd]
[pkrvmberfyhpb9w:06941] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc4ffa2a1ca]
[pkrvmberfyhpb9w:06941] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc4ffa2a28b]
[pkrvmberfyhpb9w:06941] [11] plumed_master(+0x15365)[0x559804a6c365]
[pkrvmberfyhpb9w:06941] *** End of error message ***
</pre>
{% endraw %}
