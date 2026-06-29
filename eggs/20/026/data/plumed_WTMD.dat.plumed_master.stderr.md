**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s58 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:10102] *** Process received signal ***
[runnervmmklqx:10102] Signal: Aborted (6)
[runnervmmklqx:10102] Signal code:  (-6)
[runnervmmklqx:10102] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f944f045330]
[runnervmmklqx:10102] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f944f09eb2c]
[runnervmmklqx:10102] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f944f04527e]
[runnervmmklqx:10102] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f944f0288ff]
[runnervmmklqx:10102] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f944f4a5ff5]
[runnervmmklqx:10102] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f944f4bb0da]
[runnervmmklqx:10102] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f944f4a5a55]
[runnervmmklqx:10102] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f944f4a5a6f]
[runnervmmklqx:10102] [ 8] plumed_master(+0x146dd)[0x5644a2d5d6dd]
[runnervmmklqx:10102] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f944f02a1ca]
[runnervmmklqx:10102] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f944f02a28b]
[runnervmmklqx:10102] [11] plumed_master(+0x15365)[0x5644a2d5e365]
[runnervmmklqx:10102] *** End of error message ***
</pre>
{% endraw %}
