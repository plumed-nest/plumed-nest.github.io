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
[runnervmmklqx:07334] *** Process received signal ***
[runnervmmklqx:07334] Signal: Aborted (6)
[runnervmmklqx:07334] Signal code:  (-6)
[runnervmmklqx:07334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f767e645330]
[runnervmmklqx:07334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f767e69eb2c]
[runnervmmklqx:07334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f767e64527e]
[runnervmmklqx:07334] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f767e6288ff]
[runnervmmklqx:07334] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f767eaa5ff5]
[runnervmmklqx:07334] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f767eabb0da]
[runnervmmklqx:07334] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f767eaa5a55]
[runnervmmklqx:07334] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f767eaa5a6f]
[runnervmmklqx:07334] [ 8] plumed_master(+0x146dd)[0x559073a9b6dd]
[runnervmmklqx:07334] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f767e62a1ca]
[runnervmmklqx:07334] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f767e62a28b]
[runnervmmklqx:07334] [11] plumed_master(+0x15365)[0x559073a9c365]
[runnervmmklqx:07334] *** End of error message ***
</pre>
{% endraw %}
