**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az2035-366:11876] *** Process received signal ***
[fv-az2035-366:11876] Signal: Aborted (6)
[fv-az2035-366:11876] Signal code:  (-6)
[fv-az2035-366:11876] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcb77e45330]
[fv-az2035-366:11876] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcb77e9eb2c]
[fv-az2035-366:11876] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcb77e4527e]
[fv-az2035-366:11876] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcb77e288ff]
[fv-az2035-366:11876] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcb782a5ff5]
[fv-az2035-366:11876] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcb782bb0da]
[fv-az2035-366:11876] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcb782a5a55]
[fv-az2035-366:11876] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcb782a5a6f]
[fv-az2035-366:11876] [ 8] plumed(+0x146dd)[0x56315311d6dd]
[fv-az2035-366:11876] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcb77e2a1ca]
[fv-az2035-366:11876] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcb77e2a28b]
[fv-az2035-366:11876] [11] plumed(+0x15365)[0x56315311e365]
[fv-az2035-366:11876] *** End of error message ***
</pre>
{% endraw %}
