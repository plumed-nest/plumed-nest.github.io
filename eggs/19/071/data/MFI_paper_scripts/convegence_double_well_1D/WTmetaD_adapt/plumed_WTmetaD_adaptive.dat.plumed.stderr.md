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
[pkrvmpptgkbjq6m:10641] *** Process received signal ***
[pkrvmpptgkbjq6m:10641] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10641] Signal code:  (-6)
[pkrvmpptgkbjq6m:10641] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd8c2c45330]
[pkrvmpptgkbjq6m:10641] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd8c2c9eb2c]
[pkrvmpptgkbjq6m:10641] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd8c2c4527e]
[pkrvmpptgkbjq6m:10641] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8c2c288ff]
[pkrvmpptgkbjq6m:10641] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd8c30a5ff5]
[pkrvmpptgkbjq6m:10641] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd8c30bb0da]
[pkrvmpptgkbjq6m:10641] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd8c30a5a55]
[pkrvmpptgkbjq6m:10641] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd8c30a5a6f]
[pkrvmpptgkbjq6m:10641] [ 8] plumed(+0x146dd)[0x55e18968b6dd]
[pkrvmpptgkbjq6m:10641] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd8c2c2a1ca]
[pkrvmpptgkbjq6m:10641] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd8c2c2a28b]
[pkrvmpptgkbjq6m:10641] [11] plumed(+0x15365)[0x55e18968c365]
[pkrvmpptgkbjq6m:10641] *** End of error message ***
</pre>
{% endraw %}
