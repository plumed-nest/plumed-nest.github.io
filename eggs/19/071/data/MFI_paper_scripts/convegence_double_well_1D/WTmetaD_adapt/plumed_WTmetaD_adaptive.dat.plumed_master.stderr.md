**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmq0rgcvqdmg:12144] *** Process received signal ***
[pkrvmq0rgcvqdmg:12144] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12144] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12144] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe5be45330]
[pkrvmq0rgcvqdmg:12144] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe5be9eb2c]
[pkrvmq0rgcvqdmg:12144] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe5be4527e]
[pkrvmq0rgcvqdmg:12144] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe5be288ff]
[pkrvmq0rgcvqdmg:12144] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe5c2a5ff5]
[pkrvmq0rgcvqdmg:12144] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe5c2bb0da]
[pkrvmq0rgcvqdmg:12144] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe5c2a5a55]
[pkrvmq0rgcvqdmg:12144] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe5c2a5a6f]
[pkrvmq0rgcvqdmg:12144] [ 8] plumed_master(+0x146dd)[0x55e5aef5b6dd]
[pkrvmq0rgcvqdmg:12144] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe5be2a1ca]
[pkrvmq0rgcvqdmg:12144] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe5be2a28b]
[pkrvmq0rgcvqdmg:12144] [11] plumed_master(+0x15365)[0x55e5aef5c365]
[pkrvmq0rgcvqdmg:12144] *** End of error message ***
</pre>
{% endraw %}
