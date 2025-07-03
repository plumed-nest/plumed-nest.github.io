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
[pkrvmbietmlfzoi:12233] *** Process received signal ***
[pkrvmbietmlfzoi:12233] Signal: Aborted (6)
[pkrvmbietmlfzoi:12233] Signal code:  (-6)
[pkrvmbietmlfzoi:12233] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f666ce45330]
[pkrvmbietmlfzoi:12233] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f666ce9eb2c]
[pkrvmbietmlfzoi:12233] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f666ce4527e]
[pkrvmbietmlfzoi:12233] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f666ce288ff]
[pkrvmbietmlfzoi:12233] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f666d2a5ff5]
[pkrvmbietmlfzoi:12233] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f666d2bb0da]
[pkrvmbietmlfzoi:12233] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f666d2a5a55]
[pkrvmbietmlfzoi:12233] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f666d2a5a6f]
[pkrvmbietmlfzoi:12233] [ 8] plumed(+0x146dd)[0x560358cf66dd]
[pkrvmbietmlfzoi:12233] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f666ce2a1ca]
[pkrvmbietmlfzoi:12233] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f666ce2a28b]
[pkrvmbietmlfzoi:12233] [11] plumed(+0x15365)[0x560358cf7365]
[pkrvmbietmlfzoi:12233] *** End of error message ***
</pre>
{% endraw %}
