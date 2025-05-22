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
[pkrvmf6wy0o8zjz:38055] *** Process received signal ***
[pkrvmf6wy0o8zjz:38055] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38055] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38055] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f622b645330]
[pkrvmf6wy0o8zjz:38055] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f622b69eb2c]
[pkrvmf6wy0o8zjz:38055] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f622b64527e]
[pkrvmf6wy0o8zjz:38055] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f622b6288ff]
[pkrvmf6wy0o8zjz:38055] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f622baa5ff5]
[pkrvmf6wy0o8zjz:38055] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f622babb0da]
[pkrvmf6wy0o8zjz:38055] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f622baa5a55]
[pkrvmf6wy0o8zjz:38055] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f622baa5a6f]
[pkrvmf6wy0o8zjz:38055] [ 8] plumed_master(+0x146dd)[0x55b328e546dd]
[pkrvmf6wy0o8zjz:38055] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f622b62a1ca]
[pkrvmf6wy0o8zjz:38055] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f622b62a28b]
[pkrvmf6wy0o8zjz:38055] [11] plumed_master(+0x15365)[0x55b328e55365]
[pkrvmf6wy0o8zjz:38055] *** End of error message ***
</pre>
{% endraw %}
