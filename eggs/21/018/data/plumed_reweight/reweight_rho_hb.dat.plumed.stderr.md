**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed.stderr.txt.zip) 
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
[runnervmvrwv9:10213] *** Process received signal ***
[runnervmvrwv9:10213] Signal: Aborted (6)
[runnervmvrwv9:10213] Signal code:  (-6)
[runnervmvrwv9:10213] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef72845330]
[runnervmvrwv9:10213] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef7289eb2c]
[runnervmvrwv9:10213] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef7284527e]
[runnervmvrwv9:10213] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef728288ff]
[runnervmvrwv9:10213] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef72ca5ff5]
[runnervmvrwv9:10213] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef72cbb0da]
[runnervmvrwv9:10213] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef72ca5a55]
[runnervmvrwv9:10213] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef72ca5a6f]
[runnervmvrwv9:10213] [ 8] plumed(+0x146dd)[0x5618a15176dd]
[runnervmvrwv9:10213] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef7282a1ca]
[runnervmvrwv9:10213] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef7282a28b]
[runnervmvrwv9:10213] [11] plumed(+0x15365)[0x5618a1518365]
[runnervmvrwv9:10213] *** End of error message ***
</pre>
{% endraw %}
