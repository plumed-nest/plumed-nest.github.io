**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[pkrvmberfyhpb9w:08252] *** Process received signal ***
[pkrvmberfyhpb9w:08252] Signal: Aborted (6)
[pkrvmberfyhpb9w:08252] Signal code:  (-6)
[pkrvmberfyhpb9w:08252] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f01cb645330]
[pkrvmberfyhpb9w:08252] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f01cb69eb2c]
[pkrvmberfyhpb9w:08252] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f01cb64527e]
[pkrvmberfyhpb9w:08252] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01cb6288ff]
[pkrvmberfyhpb9w:08252] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01cbaa5ff5]
[pkrvmberfyhpb9w:08252] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01cbabb0da]
[pkrvmberfyhpb9w:08252] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01cbaa5a55]
[pkrvmberfyhpb9w:08252] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01cbaa5a6f]
[pkrvmberfyhpb9w:08252] [ 8] plumed(+0x146dd)[0x5653aa6646dd]
[pkrvmberfyhpb9w:08252] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f01cb62a1ca]
[pkrvmberfyhpb9w:08252] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f01cb62a28b]
[pkrvmberfyhpb9w:08252] [11] plumed(+0x15365)[0x5653aa665365]
[pkrvmberfyhpb9w:08252] *** End of error message ***
</pre>
{% endraw %}
