**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[pkrvmberfyhpb9w:10349] *** Process received signal ***
[pkrvmberfyhpb9w:10349] Signal: Aborted (6)
[pkrvmberfyhpb9w:10349] Signal code:  (-6)
[pkrvmberfyhpb9w:10349] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4bf7645330]
[pkrvmberfyhpb9w:10349] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4bf769eb2c]
[pkrvmberfyhpb9w:10349] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4bf764527e]
[pkrvmberfyhpb9w:10349] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4bf76288ff]
[pkrvmberfyhpb9w:10349] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4bf7aa5ff5]
[pkrvmberfyhpb9w:10349] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4bf7abb0da]
[pkrvmberfyhpb9w:10349] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4bf7aa5a55]
[pkrvmberfyhpb9w:10349] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4bf7aa5a6f]
[pkrvmberfyhpb9w:10349] [ 8] plumed_master(+0x146dd)[0x55d45fba96dd]
[pkrvmberfyhpb9w:10349] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4bf762a1ca]
[pkrvmberfyhpb9w:10349] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4bf762a28b]
[pkrvmberfyhpb9w:10349] [11] plumed_master(+0x15365)[0x55d45fbaa365]
[pkrvmberfyhpb9w:10349] *** End of error message ***
</pre>
{% endraw %}
