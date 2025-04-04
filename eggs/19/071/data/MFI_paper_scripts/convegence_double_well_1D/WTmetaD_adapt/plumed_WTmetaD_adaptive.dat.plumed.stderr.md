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
[fv-az1719-476:12990] *** Process received signal ***
[fv-az1719-476:12990] Signal: Aborted (6)
[fv-az1719-476:12990] Signal code:  (-6)
[fv-az1719-476:12990] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f17f3c45330]
[fv-az1719-476:12990] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f17f3c9eb2c]
[fv-az1719-476:12990] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f17f3c4527e]
[fv-az1719-476:12990] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f17f3c288ff]
[fv-az1719-476:12990] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f17f40a5ff5]
[fv-az1719-476:12990] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f17f40bb0da]
[fv-az1719-476:12990] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f17f40a5a55]
[fv-az1719-476:12990] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f17f40a5a6f]
[fv-az1719-476:12990] [ 8] plumed(+0x146dd)[0x56348cff16dd]
[fv-az1719-476:12990] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f17f3c2a1ca]
[fv-az1719-476:12990] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f17f3c2a28b]
[fv-az1719-476:12990] [11] plumed(+0x15365)[0x56348cff2365]
[fv-az1719-476:12990] *** End of error message ***
</pre>
{% endraw %}
