**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmmklqx:09943] *** Process received signal ***
[runnervmmklqx:09943] Signal: Aborted (6)
[runnervmmklqx:09943] Signal code:  (-6)
[runnervmmklqx:09943] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc19045330]
[runnervmmklqx:09943] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc1909eb2c]
[runnervmmklqx:09943] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc1904527e]
[runnervmmklqx:09943] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc190288ff]
[runnervmmklqx:09943] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc194a5ff5]
[runnervmmklqx:09943] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc194bb0da]
[runnervmmklqx:09943] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc194a5a55]
[runnervmmklqx:09943] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc194a5a6f]
[runnervmmklqx:09943] [ 8] plumed_master(+0x146dd)[0x561c3fb076dd]
[runnervmmklqx:09943] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc1902a1ca]
[runnervmmklqx:09943] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc1902a28b]
[runnervmmklqx:09943] [11] plumed_master(+0x15365)[0x561c3fb08365]
[runnervmmklqx:09943] *** End of error message ***
</pre>
{% endraw %}
