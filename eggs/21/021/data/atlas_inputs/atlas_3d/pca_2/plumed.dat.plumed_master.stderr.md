**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[pkrvmberfyhpb9w:10144] *** Process received signal ***
[pkrvmberfyhpb9w:10144] Signal: Aborted (6)
[pkrvmberfyhpb9w:10144] Signal code:  (-6)
[pkrvmberfyhpb9w:10144] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f04ce645330]
[pkrvmberfyhpb9w:10144] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f04ce69eb2c]
[pkrvmberfyhpb9w:10144] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f04ce64527e]
[pkrvmberfyhpb9w:10144] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f04ce6288ff]
[pkrvmberfyhpb9w:10144] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f04ceaa5ff5]
[pkrvmberfyhpb9w:10144] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f04ceabb0da]
[pkrvmberfyhpb9w:10144] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f04ceaa5a55]
[pkrvmberfyhpb9w:10144] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f04ceaa5a6f]
[pkrvmberfyhpb9w:10144] [ 8] plumed_master(+0x146dd)[0x559727a4d6dd]
[pkrvmberfyhpb9w:10144] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f04ce62a1ca]
[pkrvmberfyhpb9w:10144] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f04ce62a28b]
[pkrvmberfyhpb9w:10144] [11] plumed_master(+0x15365)[0x559727a4e365]
[pkrvmberfyhpb9w:10144] *** End of error message ***
</pre>
{% endraw %}
