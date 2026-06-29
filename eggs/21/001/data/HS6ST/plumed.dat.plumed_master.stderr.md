**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:09635] *** Process received signal ***
[runnervmmklqx:09635] Signal: Aborted (6)
[runnervmmklqx:09635] Signal code:  (-6)
[runnervmmklqx:09635] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb228845330]
[runnervmmklqx:09635] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb22889eb2c]
[runnervmmklqx:09635] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb22884527e]
[runnervmmklqx:09635] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2288288ff]
[runnervmmklqx:09635] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb228ca5ff5]
[runnervmmklqx:09635] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb228cbb0da]
[runnervmmklqx:09635] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb228ca5a55]
[runnervmmklqx:09635] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb228ca5a6f]
[runnervmmklqx:09635] [ 8] plumed_master(+0x146dd)[0x5610b0b1a6dd]
[runnervmmklqx:09635] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb22882a1ca]
[runnervmmklqx:09635] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb22882a28b]
[runnervmmklqx:09635] [11] plumed_master(+0x15365)[0x5610b0b1b365]
[runnervmmklqx:09635] *** End of error message ***
</pre>
{% endraw %}
