**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmberfyhpb9w:12194] *** Process received signal ***
[pkrvmberfyhpb9w:12194] Signal: Aborted (6)
[pkrvmberfyhpb9w:12194] Signal code:  (-6)
[pkrvmberfyhpb9w:12194] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc9fde45330]
[pkrvmberfyhpb9w:12194] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc9fde9eb2c]
[pkrvmberfyhpb9w:12194] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc9fde4527e]
[pkrvmberfyhpb9w:12194] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9fde288ff]
[pkrvmberfyhpb9w:12194] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9fe2a5ff5]
[pkrvmberfyhpb9w:12194] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9fe2bb0da]
[pkrvmberfyhpb9w:12194] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9fe2a5a55]
[pkrvmberfyhpb9w:12194] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9fe2a5a6f]
[pkrvmberfyhpb9w:12194] [ 8] plumed(+0x146dd)[0x55f3f4df76dd]
[pkrvmberfyhpb9w:12194] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc9fde2a1ca]
[pkrvmberfyhpb9w:12194] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc9fde2a28b]
[pkrvmberfyhpb9w:12194] [11] plumed(+0x15365)[0x55f3f4df8365]
[pkrvmberfyhpb9w:12194] *** End of error message ***
</pre>
{% endraw %}
