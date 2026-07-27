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
[runnervmvrwv9:10228] *** Process received signal ***
[runnervmvrwv9:10228] Signal: Aborted (6)
[runnervmvrwv9:10228] Signal code:  (-6)
[runnervmvrwv9:10228] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc5a045330]
[runnervmvrwv9:10228] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc5a09eb2c]
[runnervmvrwv9:10228] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc5a04527e]
[runnervmvrwv9:10228] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc5a0288ff]
[runnervmvrwv9:10228] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc5a4a5ff5]
[runnervmvrwv9:10228] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc5a4bb0da]
[runnervmvrwv9:10228] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc5a4a5a55]
[runnervmvrwv9:10228] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc5a4a5a6f]
[runnervmvrwv9:10228] [ 8] plumed_master(+0x146dd)[0x5619ca5886dd]
[runnervmvrwv9:10228] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc5a02a1ca]
[runnervmvrwv9:10228] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc5a02a28b]
[runnervmvrwv9:10228] [11] plumed_master(+0x15365)[0x5619ca589365]
[runnervmvrwv9:10228] *** End of error message ***
</pre>
{% endraw %}
