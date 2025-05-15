**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmberfyhpb9w:08163] *** Process received signal ***
[pkrvmberfyhpb9w:08163] Signal: Aborted (6)
[pkrvmberfyhpb9w:08163] Signal code:  (-6)
[pkrvmberfyhpb9w:08163] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f783be45330]
[pkrvmberfyhpb9w:08163] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f783be9eb2c]
[pkrvmberfyhpb9w:08163] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f783be4527e]
[pkrvmberfyhpb9w:08163] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f783be288ff]
[pkrvmberfyhpb9w:08163] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f783c2a5ff5]
[pkrvmberfyhpb9w:08163] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f783c2bb0da]
[pkrvmberfyhpb9w:08163] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f783c2a5a55]
[pkrvmberfyhpb9w:08163] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f783c2a5a6f]
[pkrvmberfyhpb9w:08163] [ 8] plumed_master(+0x146dd)[0x55c1390d06dd]
[pkrvmberfyhpb9w:08163] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f783be2a1ca]
[pkrvmberfyhpb9w:08163] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f783be2a28b]
[pkrvmberfyhpb9w:08163] [11] plumed_master(+0x15365)[0x55c1390d1365]
[pkrvmberfyhpb9w:08163] *** End of error message ***
</pre>
{% endraw %}
