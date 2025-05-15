**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[pkrvmberfyhpb9w:07658] *** Process received signal ***
[pkrvmberfyhpb9w:07658] Signal: Aborted (6)
[pkrvmberfyhpb9w:07658] Signal code:  (-6)
[pkrvmberfyhpb9w:07658] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7d3b645330]
[pkrvmberfyhpb9w:07658] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7d3b69eb2c]
[pkrvmberfyhpb9w:07658] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7d3b64527e]
[pkrvmberfyhpb9w:07658] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7d3b6288ff]
[pkrvmberfyhpb9w:07658] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7d3baa5ff5]
[pkrvmberfyhpb9w:07658] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7d3babb0da]
[pkrvmberfyhpb9w:07658] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7d3baa5a55]
[pkrvmberfyhpb9w:07658] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7d3baa5a6f]
[pkrvmberfyhpb9w:07658] [ 8] plumed_master(+0x146dd)[0x56001d9876dd]
[pkrvmberfyhpb9w:07658] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7d3b62a1ca]
[pkrvmberfyhpb9w:07658] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7d3b62a28b]
[pkrvmberfyhpb9w:07658] [11] plumed_master(+0x15365)[0x56001d988365]
[pkrvmberfyhpb9w:07658] *** End of error message ***
</pre>
{% endraw %}
