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
[fv-az789-879:67057] *** Process received signal ***
[fv-az789-879:67057] Signal: Aborted (6)
[fv-az789-879:67057] Signal code:  (-6)
[fv-az789-879:67057] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf5aa45330]
[fv-az789-879:67057] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf5aa9eb2c]
[fv-az789-879:67057] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf5aa4527e]
[fv-az789-879:67057] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf5aa288ff]
[fv-az789-879:67057] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf5aea5ff5]
[fv-az789-879:67057] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf5aebb0da]
[fv-az789-879:67057] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf5aea5a55]
[fv-az789-879:67057] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf5aea5a6f]
[fv-az789-879:67057] [ 8] plumed_master(+0x146dd)[0x55e20d1396dd]
[fv-az789-879:67057] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf5aa2a1ca]
[fv-az789-879:67057] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf5aa2a28b]
[fv-az789-879:67057] [11] plumed_master(+0x15365)[0x55e20d13a365]
[fv-az789-879:67057] *** End of error message ***
</pre>
{% endraw %}
