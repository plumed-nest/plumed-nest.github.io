**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[pkrvmberfyhpb9w:07695] *** Process received signal ***
[pkrvmberfyhpb9w:07695] Signal: Aborted (6)
[pkrvmberfyhpb9w:07695] Signal code:  (-6)
[pkrvmberfyhpb9w:07695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b49245330]
[pkrvmberfyhpb9w:07695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b4929eb2c]
[pkrvmberfyhpb9w:07695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b4924527e]
[pkrvmberfyhpb9w:07695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b492288ff]
[pkrvmberfyhpb9w:07695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b496a5ff5]
[pkrvmberfyhpb9w:07695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b496bb0da]
[pkrvmberfyhpb9w:07695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b496a5a55]
[pkrvmberfyhpb9w:07695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b496a5a6f]
[pkrvmberfyhpb9w:07695] [ 8] plumed(+0x146dd)[0x564a175826dd]
[pkrvmberfyhpb9w:07695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b4922a1ca]
[pkrvmberfyhpb9w:07695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b4922a28b]
[pkrvmberfyhpb9w:07695] [11] plumed(+0x15365)[0x564a17583365]
[pkrvmberfyhpb9w:07695] *** End of error message ***
</pre>
{% endraw %}
