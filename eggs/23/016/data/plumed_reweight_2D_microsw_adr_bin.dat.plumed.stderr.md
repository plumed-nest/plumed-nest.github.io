**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s15 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:05959] *** Process received signal ***
[runnervmvrwv9:05959] Signal: Aborted (6)
[runnervmvrwv9:05959] Signal code:  (-6)
[runnervmvrwv9:05959] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee98445330]
[runnervmvrwv9:05959] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee9849eb2c]
[runnervmvrwv9:05959] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee9844527e]
[runnervmvrwv9:05959] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee984288ff]
[runnervmvrwv9:05959] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee988a5ff5]
[runnervmvrwv9:05959] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee988bb0da]
[runnervmvrwv9:05959] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee988a5a55]
[runnervmvrwv9:05959] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee988a5a6f]
[runnervmvrwv9:05959] [ 8] plumed(+0x146dd)[0x564a920d96dd]
[runnervmvrwv9:05959] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee9842a1ca]
[runnervmvrwv9:05959] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee9842a28b]
[runnervmvrwv9:05959] [11] plumed(+0x15365)[0x564a920da365]
[runnervmvrwv9:05959] *** End of error message ***
</pre>
{% endraw %}
