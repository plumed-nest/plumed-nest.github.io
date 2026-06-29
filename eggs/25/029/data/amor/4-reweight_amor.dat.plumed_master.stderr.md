**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./amor/4-reweight_amor.dat   
Download: [zipped raw stdout](4-reweight_amor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_amor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s33 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04601] *** Process received signal ***
[runnervmmklqx:04601] Signal: Aborted (6)
[runnervmmklqx:04601] Signal code:  (-6)
[runnervmmklqx:04601] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd21245330]
[runnervmmklqx:04601] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd2129eb2c]
[runnervmmklqx:04601] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd2124527e]
[runnervmmklqx:04601] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd212288ff]
[runnervmmklqx:04601] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd216a5ff5]
[runnervmmklqx:04601] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd216bb0da]
[runnervmmklqx:04601] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd216a5a55]
[runnervmmklqx:04601] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd216a5a6f]
[runnervmmklqx:04601] [ 8] plumed_master(+0x146dd)[0x5591f30c76dd]
[runnervmmklqx:04601] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd2122a1ca]
[runnervmmklqx:04601] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd2122a28b]
[runnervmmklqx:04601] [11] plumed_master(+0x15365)[0x5591f30c8365]
[runnervmmklqx:04601] *** End of error message ***
</pre>
{% endraw %}
