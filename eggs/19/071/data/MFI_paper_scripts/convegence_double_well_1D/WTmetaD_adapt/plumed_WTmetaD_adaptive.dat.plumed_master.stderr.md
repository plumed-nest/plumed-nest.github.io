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
[pkrvmxyh4eaekms:13308] *** Process received signal ***
[pkrvmxyh4eaekms:13308] Signal: Aborted (6)
[pkrvmxyh4eaekms:13308] Signal code:  (-6)
[pkrvmxyh4eaekms:13308] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd73f645330]
[pkrvmxyh4eaekms:13308] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd73f69eb2c]
[pkrvmxyh4eaekms:13308] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd73f64527e]
[pkrvmxyh4eaekms:13308] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd73f6288ff]
[pkrvmxyh4eaekms:13308] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd73faa5ff5]
[pkrvmxyh4eaekms:13308] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd73fabb0da]
[pkrvmxyh4eaekms:13308] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd73faa5a55]
[pkrvmxyh4eaekms:13308] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd73faa5a6f]
[pkrvmxyh4eaekms:13308] [ 8] plumed_master(+0x146dd)[0x55da2a6786dd]
[pkrvmxyh4eaekms:13308] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd73f62a1ca]
[pkrvmxyh4eaekms:13308] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd73f62a28b]
[pkrvmxyh4eaekms:13308] [11] plumed_master(+0x15365)[0x55da2a679365]
[pkrvmxyh4eaekms:13308] *** End of error message ***
</pre>
{% endraw %}
