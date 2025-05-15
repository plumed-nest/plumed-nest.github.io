**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmberfyhpb9w:12210] *** Process received signal ***
[pkrvmberfyhpb9w:12210] Signal: Aborted (6)
[pkrvmberfyhpb9w:12210] Signal code:  (-6)
[pkrvmberfyhpb9w:12210] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa80d445330]
[pkrvmberfyhpb9w:12210] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa80d49eb2c]
[pkrvmberfyhpb9w:12210] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa80d44527e]
[pkrvmberfyhpb9w:12210] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa80d4288ff]
[pkrvmberfyhpb9w:12210] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa80d8a5ff5]
[pkrvmberfyhpb9w:12210] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa80d8bb0da]
[pkrvmberfyhpb9w:12210] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa80d8a5a55]
[pkrvmberfyhpb9w:12210] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa80d8a5a6f]
[pkrvmberfyhpb9w:12210] [ 8] plumed_master(+0x146dd)[0x55f1aac286dd]
[pkrvmberfyhpb9w:12210] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa80d42a1ca]
[pkrvmberfyhpb9w:12210] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa80d42a28b]
[pkrvmberfyhpb9w:12210] [11] plumed_master(+0x15365)[0x55f1aac29365]
[pkrvmberfyhpb9w:12210] *** End of error message ***
</pre>
{% endraw %}
