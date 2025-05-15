**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[pkrvmberfyhpb9w:08268] *** Process received signal ***
[pkrvmberfyhpb9w:08268] Signal: Aborted (6)
[pkrvmberfyhpb9w:08268] Signal code:  (-6)
[pkrvmberfyhpb9w:08268] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f216da45330]
[pkrvmberfyhpb9w:08268] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f216da9eb2c]
[pkrvmberfyhpb9w:08268] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f216da4527e]
[pkrvmberfyhpb9w:08268] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f216da288ff]
[pkrvmberfyhpb9w:08268] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f216dea5ff5]
[pkrvmberfyhpb9w:08268] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f216debb0da]
[pkrvmberfyhpb9w:08268] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f216dea5a55]
[pkrvmberfyhpb9w:08268] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f216dea5a6f]
[pkrvmberfyhpb9w:08268] [ 8] plumed_master(+0x146dd)[0x55775cb976dd]
[pkrvmberfyhpb9w:08268] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f216da2a1ca]
[pkrvmberfyhpb9w:08268] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f216da2a28b]
[pkrvmberfyhpb9w:08268] [11] plumed_master(+0x15365)[0x55775cb98365]
[pkrvmberfyhpb9w:08268] *** End of error message ***
</pre>
{% endraw %}
