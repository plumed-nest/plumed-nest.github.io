**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:09345] *** Process received signal ***
[runnervmmklqx:09345] Signal: Aborted (6)
[runnervmmklqx:09345] Signal code:  (-6)
[runnervmmklqx:09345] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f059a445330]
[runnervmmklqx:09345] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f059a49eb2c]
[runnervmmklqx:09345] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f059a44527e]
[runnervmmklqx:09345] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f059a4288ff]
[runnervmmklqx:09345] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f059a8a5ff5]
[runnervmmklqx:09345] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f059a8bb0da]
[runnervmmklqx:09345] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f059a8a5a55]
[runnervmmklqx:09345] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f059a8a5a6f]
[runnervmmklqx:09345] [ 8] plumed_master(+0x146dd)[0x561a7cbeb6dd]
[runnervmmklqx:09345] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f059a42a1ca]
[runnervmmklqx:09345] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f059a42a28b]
[runnervmmklqx:09345] [11] plumed_master(+0x15365)[0x561a7cbec365]
[runnervmmklqx:09345] *** End of error message ***
</pre>
{% endraw %}
