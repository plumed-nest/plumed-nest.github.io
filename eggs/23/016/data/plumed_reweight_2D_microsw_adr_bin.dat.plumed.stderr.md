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
[runnervmmklqx:07267] *** Process received signal ***
[runnervmmklqx:07267] Signal: Aborted (6)
[runnervmmklqx:07267] Signal code:  (-6)
[runnervmmklqx:07267] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f179ee45330]
[runnervmmklqx:07267] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f179ee9eb2c]
[runnervmmklqx:07267] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f179ee4527e]
[runnervmmklqx:07267] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f179ee288ff]
[runnervmmklqx:07267] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f179f2a5ff5]
[runnervmmklqx:07267] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f179f2bb0da]
[runnervmmklqx:07267] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f179f2a5a55]
[runnervmmklqx:07267] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f179f2a5a6f]
[runnervmmklqx:07267] [ 8] plumed(+0x146dd)[0x55dbf68de6dd]
[runnervmmklqx:07267] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f179ee2a1ca]
[runnervmmklqx:07267] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f179ee2a28b]
[runnervmmklqx:07267] [11] plumed(+0x15365)[0x55dbf68df365]
[runnervmmklqx:07267] *** End of error message ***
</pre>
{% endraw %}
