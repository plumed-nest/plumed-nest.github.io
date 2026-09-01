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
[runnervmgx7h7:08840] *** Process received signal ***
[runnervmgx7h7:08840] Signal: Aborted (6)
[runnervmgx7h7:08840] Signal code:  (-6)
[runnervmgx7h7:08840] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f96245330]
[runnervmgx7h7:08840] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f9629ec0c]
[runnervmgx7h7:08840] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f9624527e]
[runnervmgx7h7:08840] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f962288ff]
[runnervmgx7h7:08840] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f966a5ff5]
[runnervmgx7h7:08840] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f966bb0da]
[runnervmgx7h7:08840] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f966a5a55]
[runnervmgx7h7:08840] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f966a5a6f]
[runnervmgx7h7:08840] [ 8] plumed(+0x146dd)[0x5559d60eb6dd]
[runnervmgx7h7:08840] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f9622a1ca]
[runnervmgx7h7:08840] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f9622a28b]
[runnervmgx7h7:08840] [11] plumed(+0x15365)[0x5559d60ec365]
[runnervmgx7h7:08840] *** End of error message ***
</pre>
{% endraw %}
