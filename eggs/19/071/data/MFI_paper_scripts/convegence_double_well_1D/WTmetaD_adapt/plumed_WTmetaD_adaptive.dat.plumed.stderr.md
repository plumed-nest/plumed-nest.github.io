**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmmklqx:09927] *** Process received signal ***
[runnervmmklqx:09927] Signal: Aborted (6)
[runnervmmklqx:09927] Signal code:  (-6)
[runnervmmklqx:09927] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe856245330]
[runnervmmklqx:09927] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe85629eb2c]
[runnervmmklqx:09927] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe85624527e]
[runnervmmklqx:09927] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8562288ff]
[runnervmmklqx:09927] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8566a5ff5]
[runnervmmklqx:09927] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8566bb0da]
[runnervmmklqx:09927] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8566a5a55]
[runnervmmklqx:09927] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8566a5a6f]
[runnervmmklqx:09927] [ 8] plumed(+0x146dd)[0x556a085bc6dd]
[runnervmmklqx:09927] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe85622a1ca]
[runnervmmklqx:09927] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe85622a28b]
[runnervmmklqx:09927] [11] plumed(+0x15365)[0x556a085bd365]
[runnervmmklqx:09927] *** End of error message ***
</pre>
{% endraw %}
