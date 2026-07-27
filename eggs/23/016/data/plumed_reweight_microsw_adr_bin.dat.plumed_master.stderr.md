**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s17 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:06027] *** Process received signal ***
[runnervmvrwv9:06027] Signal: Aborted (6)
[runnervmvrwv9:06027] Signal code:  (-6)
[runnervmvrwv9:06027] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff607645330]
[runnervmvrwv9:06027] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff60769eb2c]
[runnervmvrwv9:06027] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff60764527e]
[runnervmvrwv9:06027] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6076288ff]
[runnervmvrwv9:06027] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff607aa5ff5]
[runnervmvrwv9:06027] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff607abb0da]
[runnervmvrwv9:06027] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff607aa5a55]
[runnervmvrwv9:06027] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff607aa5a6f]
[runnervmvrwv9:06027] [ 8] plumed_master(+0x146dd)[0x562d8515e6dd]
[runnervmvrwv9:06027] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff60762a1ca]
[runnervmvrwv9:06027] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff60762a28b]
[runnervmvrwv9:06027] [11] plumed_master(+0x15365)[0x562d8515f365]
[runnervmvrwv9:06027] *** End of error message ***
</pre>
{% endraw %}
