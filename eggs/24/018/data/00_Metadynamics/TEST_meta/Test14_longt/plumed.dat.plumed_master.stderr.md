**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmberfyhpb9w:06211] *** Process received signal ***
[pkrvmberfyhpb9w:06211] Signal: Aborted (6)
[pkrvmberfyhpb9w:06211] Signal code:  (-6)
[pkrvmberfyhpb9w:06211] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7eff34245330]
[pkrvmberfyhpb9w:06211] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7eff3429eb2c]
[pkrvmberfyhpb9w:06211] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7eff3424527e]
[pkrvmberfyhpb9w:06211] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7eff342288ff]
[pkrvmberfyhpb9w:06211] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7eff346a5ff5]
[pkrvmberfyhpb9w:06211] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7eff346bb0da]
[pkrvmberfyhpb9w:06211] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7eff346a5a55]
[pkrvmberfyhpb9w:06211] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7eff346a5a6f]
[pkrvmberfyhpb9w:06211] [ 8] plumed_master(+0x146dd)[0x55bcc1db16dd]
[pkrvmberfyhpb9w:06211] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7eff3422a1ca]
[pkrvmberfyhpb9w:06211] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7eff3422a28b]
[pkrvmberfyhpb9w:06211] [11] plumed_master(+0x15365)[0x55bcc1db2365]
[pkrvmberfyhpb9w:06211] *** End of error message ***
</pre>
{% endraw %}
