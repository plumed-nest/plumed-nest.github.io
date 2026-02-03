**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmkj6or:07356] *** Process received signal ***
[runnervmkj6or:07356] Signal: Aborted (6)
[runnervmkj6or:07356] Signal code:  (-6)
[runnervmkj6or:07356] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f77d6445330]
[runnervmkj6or:07356] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f77d649eb2c]
[runnervmkj6or:07356] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f77d644527e]
[runnervmkj6or:07356] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77d64288ff]
[runnervmkj6or:07356] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77d68a5ff5]
[runnervmkj6or:07356] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77d68bb0da]
[runnervmkj6or:07356] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77d68a5a55]
[runnervmkj6or:07356] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77d68a5a6f]
[runnervmkj6or:07356] [ 8] plumed_master(+0x146dd)[0x55a8bc25f6dd]
[runnervmkj6or:07356] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f77d642a1ca]
[runnervmkj6or:07356] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f77d642a28b]
[runnervmkj6or:07356] [11] plumed_master(+0x15365)[0x55a8bc260365]
[runnervmkj6or:07356] *** End of error message ***
</pre>
{% endraw %}
