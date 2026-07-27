**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:07772] *** Process received signal ***
[runnervmvrwv9:07772] Signal: Aborted (6)
[runnervmvrwv9:07772] Signal code:  (-6)
[runnervmvrwv9:07772] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd368c45330]
[runnervmvrwv9:07772] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd368c9eb2c]
[runnervmvrwv9:07772] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd368c4527e]
[runnervmvrwv9:07772] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd368c288ff]
[runnervmvrwv9:07772] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3690a5ff5]
[runnervmvrwv9:07772] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3690bb0da]
[runnervmvrwv9:07772] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3690a5a55]
[runnervmvrwv9:07772] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3690a5a6f]
[runnervmvrwv9:07772] [ 8] plumed(+0x146dd)[0x55dca57f56dd]
[runnervmvrwv9:07772] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd368c2a1ca]
[runnervmvrwv9:07772] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd368c2a28b]
[runnervmvrwv9:07772] [11] plumed(+0x15365)[0x55dca57f6365]
[runnervmvrwv9:07772] *** End of error message ***
</pre>
{% endraw %}
