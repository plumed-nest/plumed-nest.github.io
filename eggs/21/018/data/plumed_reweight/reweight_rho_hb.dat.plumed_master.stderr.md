**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:08248] *** Process received signal ***
[runnervmmklqx:08248] Signal: Aborted (6)
[runnervmmklqx:08248] Signal code:  (-6)
[runnervmmklqx:08248] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc68aa45330]
[runnervmmklqx:08248] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc68aa9eb2c]
[runnervmmklqx:08248] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc68aa4527e]
[runnervmmklqx:08248] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc68aa288ff]
[runnervmmklqx:08248] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc68aea5ff5]
[runnervmmklqx:08248] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc68aebb0da]
[runnervmmklqx:08248] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc68aea5a55]
[runnervmmklqx:08248] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc68aea5a6f]
[runnervmmklqx:08248] [ 8] plumed_master(+0x146dd)[0x56387a20b6dd]
[runnervmmklqx:08248] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc68aa2a1ca]
[runnervmmklqx:08248] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc68aa2a28b]
[runnervmmklqx:08248] [11] plumed_master(+0x15365)[0x56387a20c365]
[runnervmmklqx:08248] *** End of error message ***
</pre>
{% endraw %}
