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
[fv-az1719-476:13006] *** Process received signal ***
[fv-az1719-476:13006] Signal: Aborted (6)
[fv-az1719-476:13006] Signal code:  (-6)
[fv-az1719-476:13006] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0160a45330]
[fv-az1719-476:13006] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0160a9eb2c]
[fv-az1719-476:13006] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0160a4527e]
[fv-az1719-476:13006] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0160a288ff]
[fv-az1719-476:13006] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0160ea5ff5]
[fv-az1719-476:13006] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0160ebb0da]
[fv-az1719-476:13006] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0160ea5a55]
[fv-az1719-476:13006] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0160ea5a6f]
[fv-az1719-476:13006] [ 8] plumed_master(+0x146dd)[0x56051e6996dd]
[fv-az1719-476:13006] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0160a2a1ca]
[fv-az1719-476:13006] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0160a2a28b]
[fv-az1719-476:13006] [11] plumed_master(+0x15365)[0x56051e69a365]
[fv-az1719-476:13006] *** End of error message ***
</pre>
{% endraw %}
