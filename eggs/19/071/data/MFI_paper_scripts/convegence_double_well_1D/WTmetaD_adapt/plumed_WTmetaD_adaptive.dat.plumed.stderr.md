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
[pkrvmf6wy0o8zjz:69410] *** Process received signal ***
[pkrvmf6wy0o8zjz:69410] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69410] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f38fe845330]
[pkrvmf6wy0o8zjz:69410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f38fe89eb2c]
[pkrvmf6wy0o8zjz:69410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f38fe84527e]
[pkrvmf6wy0o8zjz:69410] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f38fe8288ff]
[pkrvmf6wy0o8zjz:69410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f38feca5ff5]
[pkrvmf6wy0o8zjz:69410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f38fecbb0da]
[pkrvmf6wy0o8zjz:69410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f38feca5a55]
[pkrvmf6wy0o8zjz:69410] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f38feca5a6f]
[pkrvmf6wy0o8zjz:69410] [ 8] plumed(+0x146dd)[0x562b718a66dd]
[pkrvmf6wy0o8zjz:69410] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f38fe82a1ca]
[pkrvmf6wy0o8zjz:69410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f38fe82a28b]
[pkrvmf6wy0o8zjz:69410] [11] plumed(+0x15365)[0x562b718a7365]
[pkrvmf6wy0o8zjz:69410] *** End of error message ***
</pre>
{% endraw %}
