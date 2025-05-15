**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmberfyhpb9w:06454] *** Process received signal ***
[pkrvmberfyhpb9w:06454] Signal: Aborted (6)
[pkrvmberfyhpb9w:06454] Signal code:  (-6)
[pkrvmberfyhpb9w:06454] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e5a045330]
[pkrvmberfyhpb9w:06454] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e5a09eb2c]
[pkrvmberfyhpb9w:06454] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e5a04527e]
[pkrvmberfyhpb9w:06454] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e5a0288ff]
[pkrvmberfyhpb9w:06454] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e5a4a5ff5]
[pkrvmberfyhpb9w:06454] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e5a4bb0da]
[pkrvmberfyhpb9w:06454] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e5a4a5a55]
[pkrvmberfyhpb9w:06454] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e5a4a5a6f]
[pkrvmberfyhpb9w:06454] [ 8] plumed(+0x146dd)[0x559bf8dba6dd]
[pkrvmberfyhpb9w:06454] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e5a02a1ca]
[pkrvmberfyhpb9w:06454] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e5a02a28b]
[pkrvmberfyhpb9w:06454] [11] plumed(+0x15365)[0x559bf8dbb365]
[pkrvmberfyhpb9w:06454] *** End of error message ***
</pre>
{% endraw %}
