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
[runnervmvrwv9:09882] *** Process received signal ***
[runnervmvrwv9:09882] Signal: Aborted (6)
[runnervmvrwv9:09882] Signal code:  (-6)
[runnervmvrwv9:09882] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa7ce45330]
[runnervmvrwv9:09882] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa7ce9eb2c]
[runnervmvrwv9:09882] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa7ce4527e]
[runnervmvrwv9:09882] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa7ce288ff]
[runnervmvrwv9:09882] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa7d2a5ff5]
[runnervmvrwv9:09882] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa7d2bb0da]
[runnervmvrwv9:09882] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa7d2a5a55]
[runnervmvrwv9:09882] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa7d2a5a6f]
[runnervmvrwv9:09882] [ 8] plumed_master(+0x146dd)[0x55fe0a8b16dd]
[runnervmvrwv9:09882] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa7ce2a1ca]
[runnervmvrwv9:09882] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa7ce2a28b]
[runnervmvrwv9:09882] [11] plumed_master(+0x15365)[0x55fe0a8b2365]
[runnervmvrwv9:09882] *** End of error message ***
</pre>
{% endraw %}
