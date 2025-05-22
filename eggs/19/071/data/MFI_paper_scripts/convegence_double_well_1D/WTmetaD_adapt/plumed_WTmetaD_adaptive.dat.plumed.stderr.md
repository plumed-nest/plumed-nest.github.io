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
[pkrvmf6wy0o8zjz:38039] *** Process received signal ***
[pkrvmf6wy0o8zjz:38039] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38039] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38039] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f75fb445330]
[pkrvmf6wy0o8zjz:38039] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f75fb49eb2c]
[pkrvmf6wy0o8zjz:38039] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f75fb44527e]
[pkrvmf6wy0o8zjz:38039] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f75fb4288ff]
[pkrvmf6wy0o8zjz:38039] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f75fb8a5ff5]
[pkrvmf6wy0o8zjz:38039] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f75fb8bb0da]
[pkrvmf6wy0o8zjz:38039] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f75fb8a5a55]
[pkrvmf6wy0o8zjz:38039] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f75fb8a5a6f]
[pkrvmf6wy0o8zjz:38039] [ 8] plumed(+0x146dd)[0x55c57e59c6dd]
[pkrvmf6wy0o8zjz:38039] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f75fb42a1ca]
[pkrvmf6wy0o8zjz:38039] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f75fb42a28b]
[pkrvmf6wy0o8zjz:38039] [11] plumed(+0x15365)[0x55c57e59d365]
[pkrvmf6wy0o8zjz:38039] *** End of error message ***
</pre>
{% endraw %}
