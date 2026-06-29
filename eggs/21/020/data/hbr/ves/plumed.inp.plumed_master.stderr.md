**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:09499] *** Process received signal ***
[runnervmmklqx:09499] Signal: Aborted (6)
[runnervmmklqx:09499] Signal code:  (-6)
[runnervmmklqx:09499] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6003e45330]
[runnervmmklqx:09499] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6003e9eb2c]
[runnervmmklqx:09499] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6003e4527e]
[runnervmmklqx:09499] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6003e288ff]
[runnervmmklqx:09499] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60042a5ff5]
[runnervmmklqx:09499] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60042bb0da]
[runnervmmklqx:09499] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60042a5a55]
[runnervmmklqx:09499] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60042a5a6f]
[runnervmmklqx:09499] [ 8] plumed_master(+0x146dd)[0x55f8e1b646dd]
[runnervmmklqx:09499] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6003e2a1ca]
[runnervmmklqx:09499] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6003e2a28b]
[runnervmmklqx:09499] [11] plumed_master(+0x15365)[0x55f8e1b65365]
[runnervmmklqx:09499] *** End of error message ***
</pre>
{% endraw %}
