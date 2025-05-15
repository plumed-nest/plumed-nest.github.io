**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvmberfyhpb9w:07178] *** Process received signal ***
[pkrvmberfyhpb9w:07178] Signal: Aborted (6)
[pkrvmberfyhpb9w:07178] Signal code:  (-6)
[pkrvmberfyhpb9w:07178] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8833e45330]
[pkrvmberfyhpb9w:07178] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8833e9eb2c]
[pkrvmberfyhpb9w:07178] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8833e4527e]
[pkrvmberfyhpb9w:07178] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8833e288ff]
[pkrvmberfyhpb9w:07178] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88342a5ff5]
[pkrvmberfyhpb9w:07178] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88342bb0da]
[pkrvmberfyhpb9w:07178] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88342a5a55]
[pkrvmberfyhpb9w:07178] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88342a5a6f]
[pkrvmberfyhpb9w:07178] [ 8] plumed_master(+0x146dd)[0x564bb831e6dd]
[pkrvmberfyhpb9w:07178] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8833e2a1ca]
[pkrvmberfyhpb9w:07178] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8833e2a28b]
[pkrvmberfyhpb9w:07178] [11] plumed_master(+0x15365)[0x564bb831f365]
[pkrvmberfyhpb9w:07178] *** End of error message ***
</pre>
{% endraw %}
